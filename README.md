# Sonatype SCM Features 
## for Smuckers

Showcase for 4 major languages:
1. JavaScript (node)

    https://help.sonatype.com/en/npm-application-analysis.html
    ```
    npm install
    ```
2. Python (pypi)

    https://help.sonatype.com/en/python-application-analysis.html
    ```
    pip freeze > requirements.txt
    pip download -r requirements.txt -d pip_modules
    ```
3. .NET/C# (NuGet)
    
    https://help.sonatype.com/en/nuget-application-analysis.html
    ```
    dotnet tool install --global CycloneDX
    dotnet restore
    dotnet CycloneDX SonatypeSCA\SonatypeSCA.csproj -o SonatypeSCA\
    ```
4. R (CRAN)
    
    https://help.sonatype.com/en/r--cran--application-analysis.html
