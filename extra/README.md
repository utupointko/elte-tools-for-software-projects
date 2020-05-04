# Extra tools

## 7. CI Extra Tools

#### **Tools for Code Verification**  
*"The earlier it is caught, the cheaper it is to fix."*

* Compiler Settings / Flags (warnings, warnings as errors -> No Warning Policy)
* Static Analyzers
    * List of Tools per Language https://en.wikipedia.org/wiki/List_of_tools_for_static_code_analysis
    * FindBugs http://findbugs.sourceforge.net/ also see http://www.methodsandtools.com/tools/findbugs.php
    * Cppcheck http://cppcheck.sourceforge.net/ also see Demo
    * PMD https://pmd.github.io/ also see Documentation
        * CPD = copy-paste-detector - code duplication detection
    * SonarQube https://www.sonarqube.org/
    * Clang Static Analyzer https://clang-analyzer.llvm.org/
    * Clang Tidy https://clang.llvm.org/extra/clang-tidy/
    * CodeChecker (@ELTE) https://github.com/Ericsson/codechecker
    * Pylint https://www.pylint.org/
* Coverage Analysis
    * EclEmma http://www.eclemma.org/
    * gcov https://gcc.gnu.org/onlinedocs/gcc/Gcov.html and [gcov.cpp.html](gcov.cpp.html)
* Profiling
    * List of Performance Analysis Tools https://en.wikipedia.org/wiki/List_of_performance_analysis_tools
    * VisualVM https://visualvm.github.io/
    * Gprof https://en.wikipedia.org/wiki/Gprof
 
<br>

#### **Tools for Code Maintainability**

* Documentation Generators
    * Comparison of Documentation Generators https://en.wikipedia.org/wiki/Comparison_of_documentation_generators
    * Javadoc https://en.wikipedia.org/wiki/Javadoc
    * Doxygen http://doxygen.nl/
* Code Styles & Standards / Auto-Formatting
    * pep8 https://pypi.org/project/pep8/
    * flake8 https://pypi.org/project/flake8/
    * Checkstyle http://checkstyle.sourceforge.net/ also see list of checks http://checkstyle.sourceforge.net/checks.html
    * ClangFormat https://clang.llvm.org/docs/ClangFormat.html (no standard, you decide and configure)
* Code Metrics
    * Kind of Static Analysis, see tools there (Pylint, SonarQube...)