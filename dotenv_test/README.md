Dotenv is a gem that allows you to store API keys in a nice file that will remain secret, because it will never be pushed on GitHub. Via the gem, your program will be able to call on the contents of this file to use the keys.

How it works ?
We will put all the API keys in a file whose full name is .env, then we can call them by doing ENV ["KEY_NAME"] in our Ruby program. Then in order to avoid pushing the bousin on GitHub, we will add the .env file in our .gitignore.