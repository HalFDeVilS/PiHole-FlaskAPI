# PiHole-FlaskAPI

#### This Project is used to convert and enhance the current PiHole API's Structure to Flask Cross-Origin Enabled Rest API's.

## Features

 - Can be used with various frontend frameworks like Vue, Angular, React.
 - Provides good api documentation using swagger.
 - Authentication via Web API Token or Json Web Token.
 - Introduction to new elevate db (can be used for custom branding and extended services with any frontend framework.)
 - And many more.

## System Requirements

#### This project requires python3+ and some python libraries:
 1. waitress 
 2. Flask_Cors
 3. Flask
 4. flask_swagger_ui
 5. PyJWT

These are also mentioned in requirements.txt.

## Installation

 1. Clone this project using git clone.

> git clone https://github.com/HalFDeVilS/PiHole-FlaskAPI.git
2.  Create python virtual env (Optional).
3.  Change PATH inside default.config to the path used by pihole's gravity db.
You can also change JWT-SECRET (Used for Token Created).
If you also add FTL host address using key as FTL-HOST and its value as address you want to point to.
4. Run the waitress server by executing **dns.py** from v1 folder.

## Suggestions
