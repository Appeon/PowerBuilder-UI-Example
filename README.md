# PowerBuilder-UI-Example

This demo is a PowerBuilder application, developed with Appeon PowerBuilder 2021 (https://www.appeon.com/products/powerbuilder). It demonstrates techniques to modernize the look of an application. It shows two major functionalities:

1. Integrating the RibbonBar control into a MDI application.
   -  Load a RibbonBar XML file.
   -  Customize the invoke of the Clicked event of each child control of the RibbonBar control.
   -  Dynamically create the menu under the LargeButton function.
   -  Use scripts to dynamically enable/disable the status of each control on the RibbonBar.

2. Applying the UI theme and its customization.
   -  Dynamically switch between 4 themes.
   -  Comparison between a window using the standard Theme and the customized Theme.
   -  Use Theme to customize a window and its related standard controls.
   -  Customize the Theme of a visual user object.
   -  Customize the Theme of a DataWindow.


Note: This Demo only provides the customized theme color comparison based on two themes (‘Flat Design Dark’ and ‘Flat Design Blue’).

### Sample Project Structure

The project is structured as follows.

```
|—— PowerBuilder-UI-Example Repository 
	|—— Appeon.UIDemo				PowerBuilder project source code
```

### Setting Up the Project

Download this PowerBuilder demo application, and then:

1. Open the PowerBuilder project in PowerBuilder 2021.
2. Download the database file **pbdemo2021_for_sqlanywhere.zip** from [PowerBuilder-Project-Example-Database](https://github.com/Appeon/PowerBuilder-Project-Example-Database) and restore it.
3. Configure the ODBC data source.
4. Copy the database connection string in the configured data source to replace the connection string in the original project. Note that the PWD in the connection string is masked. Please manually change it to the real password.
5. Run the PowerBuilder project.
6. You can select 'Modernization UI' to view the modernized MDI application, or select 'Tradition UI' to see the traditional MDI application. 
