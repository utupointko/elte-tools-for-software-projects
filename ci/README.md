# Continuous Integration (CI)

## 3. Build Systems History - from Autotools to CMake

#### **Build Systems**

*  Why a Build System?
*  History
*  Software Delivery & Deploy
*  Cross-Platform Build

Outlook on Build Automation:
https://en.wikipedia.org/wiki/List_of_build_automation_software

**Make:**  
Wiki: https://en.wikipedia.org/wiki/Make_(software)  
GNU Make Manual: https://www.gnu.org/software/make/manual/make.html

**Autotools:**  
Slides on Autotools: https://www.lrde.epita.fr/~adl/dl/autotools.pdf  
Autotools Mythbuster: https://autotools.io/index.html

**CMake:**  
CMake Guides: https://cmake.org/cmake/help/latest/#guides  
CMake Reference: https://cmake.org/cmake/help/latest/  
Ninja build system: https://ninja-build.org/manual.html

* * *

## 4. Build Systems - Ant, Maven, Gradle + Artifact Repositories

#### **Build Systems for Java**  
- Ant, Maven, Gradle + Artifact Repositories

<br>

Java Build Systems [slides](advbuild.pdf)

Artifact Repositories [slides](artifact-repositories.pdf)

* Software Repository
* Artifact Repository  
(Binary repository manager: https://en.wikipedia.org/wiki/Binary_repository_manager)
* Software Package Management Systems:  
https://en.wikipedia.org/wiki/List_of_software_package_management_systems

Advanced Build Summary [slides](advancedbuild.pdf)

* * *

## 5. Testing Basics

#### **Testing Basics**

* Why? CI / CD? https://en.wikipedia.org/wiki/Continuous_integration
* Simple Levels of Testing (triangle of testing)
   * 0.asserts / different builds
   * 1.unit
   * 2.integration
   * 3.system
* Real Ways of Testing
   * Types: https://www.tutorialspoint.com/software_testing/software_testing_types.htm
   * Methods: https://www.tutorialspoint.com/software_testing/software_testing_methods.htm
   * Levels: https://www.tutorialspoint.com/software_testing/software_testing_levels.htm
* Unittest frameworks
   * JUnit / JMock: See testing_java.zip and https://junit.org & http://jmock.org/
   * GTest / GMock See testing_cpp.zip and https://github.com/google/googletest
   * Nosetests https://nose.readthedocs.io
* Test Expectations: [gtesting.cpp.html](gtesting.cpp.html)

* * *

## 6. CI / CD ... towards DevOps

#### **Advanced Builds**

Multiple Builds because of

* Debug / Release / ReleaseWithDebug (+Obfuscation)
* Free / Commercial / With Extra Feature
* Release per Branch (eg: 1.4 maintenance, 2.0 new release)
* Release per Platform
* Special Builds
   * Coverage
   * Memory / Leak Checking
   * Thread Checking
 
<br>

#### **CI/CD & Automation towards DevOps -** [ci.pdf](ci.pdf)

* Jenkins https://jenkins.io/