# Module-17-Challenge
The purpose of this assignement is to make a desdription for what a regex expression is and what it does.

 # Regex tutorial for /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/

  ## Table of Contents
  1. [Description](#description)
  2. [Usage](#usage)
  3. [Contributing](#contributing)
  4. [Testing](#testing)
  5. [License](#license)
  6. [Questions](#questions)

  ## Project Description
  
A regular expression or regex for short is the arrangement of cahracters and specail characters that are used for search patterns. They are generally used with the purpose of finding patterns withing strings or even for the purpsose of validating the info that the user has put in. The example we will be looking at is going to be this  /^([a-z0-9_\.-]+)@([\da-z\.-]+)\.([a-z\.]{2,6})$/. This regex is used to make sure that the user has put in a valid email address. In the first part of this regex [a-z0-9_\.-] it is searching the users input to match for an email that starts and ends with a combination of lowercase letters. After searching for the lowercase letters the regex will then search for a combination of numbers from zero to nine. The final part of the beginning is used to search for the special characters of an underscore, foward slash, period, and hyphen. The regex then searches to make sure that the user has an at sign in their email address by using the plus sign to add on to the start of the search. The regex will then go into its next part of the search that comes after the at sign of the email which is [\da-z\.-]+)\.([a-z\.]{2,6})$/. This will start with the \d which searches for any Arabic numeral. Which is the equivalent of searching for [0-9]. Then the search continues to a search of lowercase letters and the special characters of a period or hyphen. Then we continute to add to the search for what comes next. The search will look for a period next in the email. After a period has been found it will then search for lowercase letters from a to z and a period but with a limit of two to 6 characters. The final dollar sign in this arrangement is an anchor so that it knows where to end the search algorithim. 

  ---------------------------------------------
  ## Usage

  This will help the user learn more about regexs. It will help them learn how to identify one and what the purpose they serve is.

  ---------------------------------------------
  ## Contributing

  If you woud like to add anything to this please feel free to do so or you can contact me with ideas that you have on ways to improve it.

  ---------------------------------------------

  ## License

  MIT

  ---------------------------------------------

  ## Questions

  If you have any further questions about regex's or the explanation given for the example please feel free to contact me.
  Email: noeljordan34@gmail.com
  Phone: (850)832-2701
