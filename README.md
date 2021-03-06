<div align="center">
  <a href="https://www.python.org/">
    <img src="http://ForTheBadge.com/images/badges/made-with-python.svg"
      alt="API stability" />
  </a>
</div>

<div align="center">
  <!-- Contributors -->
  <a href="https://github.com/somrajchowdhury/Python_GUI_tkinter/graphs/contributors">
    <img src="https://img.shields.io/badge/contributor(s)-1-red.svg"
      alt="API stability" />
  </a>

  <!-- Python Version -->
  <a href="https://github.com/somrajchowdhury/PythonCodes/">
    <img src="https://img.shields.io/badge/Python-3.x-blue.svg"
      alt="API stability" />
  </a>
  
  <!-- Number of Codes -->
  <a href="https://github.com/somrajchowdhury/PythonCodes/">
    <img src="https://img.shields.io/badge/4-codes-brightgreen.svg"
      alt="API stability" />
  </a>
</div>

<h1 align="center">tkinter GUI</h1>

# Python GUI programming using tkinter

> tkinter is a standard Python GUI package.

## Program List

- [Buttons in tkinter](#buttons-in-tkinter)
- [Book Management System](#book-management-system)
- [The Movie Place](#the-movie-place)
- [The Weather App](#the-weather-app)

## Buttons in tkinter

> **Check out :** [tkinterBUTTONS1.py](https://github.com/somrajchowdhury/Python_GUI_tkinter/blob/master/tkinterBUTTONS1.py)

Learn and code out most of the button types in tkinter.
> **Code Output :** 
>
> ![tkinter buttons1](https://github.com/somrajchowdhury/Python_GUI_tkinter/blob/master/img/tkinterButtons1.png "tkinter buttons1")
>

[(Back to top)](#program-list)

---

## Book Management System

This Book Management System is a CRUD (Create, Read, Update and Delete) application with a feature to search for books in the database. This application is supported with form validations and info messages as you use the various features of the application.

### Developed using :

- Python 3.7.0 <img src='https://i.imgur.com/QbZcwbk.png' width=20>
- tKinter (Tcl/Tk 8.6) <img src='https://i.imgur.com/fkNo1xh.png' width=20>
- SQLite3 3.21.0 <img src='https://i.imgur.com/n1Wjdv4.png' width=20>

### Screenshots :camera: :

| ![Add Book Window.png](https://i.imgur.com/t6e4sq9.png) |
|:--:|
| **_Add Book Window_** |

![View Book Details Window.png](https://i.imgur.com/4n7mb6V.png) |
|:--:|
|**_View Book Details Window_** |

| ![Delete Book Window.png](https://i.imgur.com/P0cOy36.png) |
|:--:|
| **_Delete Book Window_** |

| ![Update Book Window.png](https://i.imgur.com/BaQtWhz.png) |
|:--:|
| **_Update Book Window_** |

Click the button below to see the working and features of the application.

**Link :** <kbd>[Book Management System](https://protected-stream-65012.herokuapp.com/)</kbd>

[(Back to top)](#program-list)

---

## The Movie Place

*The Movie Place!* application uses an API to extract movie data using URL requests and displays the relevant retrieved data from the API on to the GUI.

### API used:

![OMDb API](https://i.imgur.com/dXPGYfZ.png)

The **OMDb** API is a RESTful web service to obtain movie information. By default all OMDb API responses are formatted as JSON. However, OMDb API also supports responses formatted as XML.

### Libraries used:

- **tkinter** - *to design the GUI*
- **pillow (PIL)** - *to make images compatible with tk GUI*
- **io** - *to encode and use images from URL*
- **requests** - *to request and read data from the API response*
- **urllib** - *to request and read data from the API response*
- **socket** - *to configure connections*
- **json** - *to load and retrieve required fields from the API response*

### Screenshots :camera: :

The first window that shows up is where you enter the name of the movie whose info you want to display on the GUI.

![enter movie name.png](https://i.imgur.com/VV3UFUL.png)

Suppose I enter **avatar** in the entry field,

![enter avatar](https://i.imgur.com/X9tKG55.png)

If the movie is found, the response is sent and the GUI looks like this,

![avatar](https://i.imgur.com/xoRt4u4.png)

If the entered movie is not found, it is notified in the GUI using a *validation message*,

![not found](https://i.imgur.com/ZzvzpUW.png)

Also, at times there might be some issues connecting to the API service, in that case you get a *message* to resumbit, where you just need to click the `SUBMIT` button again

![resubmit](https://i.imgur.com/8feFmAK.png)

*Some more screenshots*

| ![harry potter](https://i.imgur.com/5gggJ2Y.png) | ![stranger things](https://i.imgur.com/OLSyySN.png) |
|:--:|:--:|
| ![uri](https://i.imgur.com/AUSQp2X.png) | ![3 idiots](https://i.imgur.com/L2n0ZbD.png) |

[(Back to top)](#program-list)

---

## The Weather App

*The Weather App* uses an API to obtain current weather data using URL requests and displays the relevant retrieved data from the API on to the GUI.

### API used:

![OW API](https://i.imgur.com/mhQ2HUb.png)

- Access current weather data for any location including over 200,000 cities
- Current weather is frequently updated based on global models and data from more than 40,000 weather stations
- Data is available in JSON, XML, or HTML format
- Available for Free and all other paid accounts

### Libraries used:

- **tkinter** - *to design the GUI*
- **pillow (PIL)** - *to make images compatible with tk GUI*
- **io** - *to encode and use images from URL*
- **requests** - *to request and read data from the API response*
- **urllib** - *to request and read data from the API response*
- **socket** - *to configure connections*
- **json** - *to load and retrieve required fields from the API response*

### Working of *The Weather App*

The first window that shows up is where you enter the name of the location.

![first window](https://i.imgur.com/Mc0RMfp.png)

If the location is found in the API, the weather data is returned.

![weather data](https://i.imgur.com/JIqOGDM.png)

If the location you entered is not found, the GUI shows a relevant message.

![not found](https://i.imgur.com/XS15DXW.png)

Also, at times there might be some issues connecting to the API service, in that case you get a *message* to resumbit, where you just need to click the `Submit` button again.

![resubmit](https://i.imgur.com/7b47Z5O.png)

The following shows a working example of *The Weather App*

![The Weather App](https://github.com/somrajchowdhury/Python_GUI_tkinter/blob/master/img/owapiapp.gif "Weather App working")

### Screenshots :camera: :

| ![england](https://i.imgur.com/REdhBTl.png) | ![durban](https://i.imgur.com/S3KGbFs.png) | ![mysore](https://i.imgur.com/ckSqRNJ.png) |
|:--:|:--:|:--:|

[(Back to top)](#program-list)
