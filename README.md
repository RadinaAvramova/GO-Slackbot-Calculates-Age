# Slackbot Calculates Age
Welcome to the Slackbot Calculates Age project! This repository contains a Slackbot implemented in Go that calculates the age of a person based on their date of birth. The Slackbot interacts with users in Slack channels or direct messages, providing the age of the person when given their date of birth.

## Features
1. **Age Calculation:** Calculates the age of a person based on their date of birth, taking into account the current date.

2. **Interactive Slackbot:** Interacts with users in Slack channels or direct messages, accepting date of birth inputs and responding with the calculated age.

3. **Error Handling:** Handles common errors such as invalid date formats or missing inputs gracefully, providing informative messages to users when errors occur.

4. **Natural Language Processing:** Supports natural language inputs for date of birth, allowing users to input dates in various formats (e.g., "January 1, 1990", "1/1/90").

## Installation
To set up the Slackbot Calculates Age:

1. **Clone the Repository:** Clone the repository to your local machine using the following command:

git clone https://github.com/RadinaAvramova/GO-Slackbot-Calculates-Age.git

2. **Navigate to the Directory:** Change your current directory to the location of the cloned repository:

cd GO-Slackbot-Calculates-Age

3. **Install Dependencies:** Install any dependencies required for the project using Go modules or package management tools.

4. **Configure Environment Variables:** Set up environment variables required for the Slackbot, such as Slack API token or bot authentication details.

5. **Run the Application:** Start the Slackbot application using the appropriate commands for your environment.

## Usage
1. **Interact with Slackbot:** Invite the Slackbot to your Slack workspace or channel and start interacting with it by mentioning its name followed by a date of birth (e.g., "@slackbot January 1, 1990").

2. **Provide Date of Birth:** Input the date of birth in natural language or standard date formats when prompted by the Slackbot.

3. **Receive Age Calculation:** The Slackbot will calculate the age based on the provided date of birth and respond with the calculated age.

4. **Error Handling:** If there are any errors in the input (e.g., invalid date format), the Slackbot will provide informative error messages to guide users.

## Customization
1. **Date Formats:** Customize the date parsing logic to support additional date formats or languages based on the preferences of your Slack users.

2. **Response Messages:** Modify the response messages or error messages to better suit the tone and style of your Slack workspace or organization.

3. **Integration with External APIs:** Integrate with external APIs or services for additional functionality, such as retrieving timezone information or performing more advanced age calculations.
