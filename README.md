# hello-world-nodejavascriptproj

<?xml version="1.0" encoding="utf-8"?>
<Project DefaultTargets="Build" xmlns="http://schemas.microsoft.com/developer/msbuild/2003" ToolsVersion="4.0">
  <PropertyGroup>
    <VisualStudioVersion Condition="'$(VisualStudioVersion)' == ''">11.0</VisualStudioVersion>
    <VSToolsPath Condition="'$(VSToolsPath)' == ''">$(MSBuildExtensionsPath32)\Microsoft\VisualStudio\v$(VisualStudioVersion)</VSToolsPath>
    <Name>01_HelloWorld</Name>
    <RootNamespace>NodeMVA</RootNamespace>
  </PropertyGroup>
  <Import Project="$(MSBuildExtensionsPath)\$(MSBuildToolsVersion)\Microsoft.Common.props" Condition="Exists('$(MSBuildExtensionsPath)\$(MSBuildToolsVersion)\Microsoft.Common.props')" />
  <PropertyGroup>
    <Configuration Condition=" '$(Configuration)' == '' ">Debug</Configuration>
    <SchemaVersion>2.0</SchemaVersion>
    <ProjectGuid>261162a0-b746-4ea0-a307-e5e4128f9257</ProjectGuid>
    <ProjectHome>
    </ProjectHome>
    <StartupFile>app.js</StartupFile>
    <StartWebBrowser>False</StartWebBrowser>
    <SearchPath>
    </SearchPath>
    <WorkingDirectory>.</WorkingDirectory>
    <OutputPath>.</OutputPath>
    <TargetFrameworkVersion>v4.0</TargetFrameworkVersion>
    <ProjectTypeGuids>{3AF33F2E-1136-4D97-BBB7-1795711AC8B8};{9092AA53-FB77-4645-B42D-1CCCA6BD08BD}</ProjectTypeGuids>
    <ProjectView>ShowAllFiles</ProjectView>
    <StartWebBrowser>false</StartWebBrowser>
  </PropertyGroup>
  <PropertyGroup Condition=" '$(Configuration)' == 'Debug' ">
    <DebugSymbols>true</DebugSymbols>
  </PropertyGroup>
  <PropertyGroup Condition=" '$(Configuration)' == 'Release' ">
    <DebugSymbols>true</DebugSymbols>
  </PropertyGroup>
  <ItemGroup>
    <Compile Include="app.js" />
    <Content Include="package.json" />
  </ItemGroup>
  <Import Project="$(VSToolsPath)\Node.js Tools\Microsoft.NodejsTools.targets" />
</Project>
