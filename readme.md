# Caremerge Test

- This test is divided into three parts. You will implement the same task three times, each using a different control flow strategy.
- This code demonstrates a raw Node.js approach.

## Requirements

- Node 22

## Installation

Use the package manager [npm](https://docs.npmjs.com/cli/v10/commands/npm-install) to install required packages.

```bash
npm install
```

## Steps for read-only access

To start the express server, run the following

```bash
npm run dev
```

### Final Step:

Copy this endpoint [localhost:3001/I/want/title/?address=google.com&address=www.dawn.com/events/](localhost:3001/I/want/title/?address=google.com&address=www.dawn.com/events/) and paste it in the url of the postman or thunderClient by setting GET method.

### Response:

```
<html>

<head></head>

<body>
    <h1>Following are the titles of given websites:</h1>
    <ul>
        <li>http://www.google.com/ - "Google"</li>
        <li>https://www.dawn.com/events/ - "Events - DAWN.COM"</li>
    </ul>
</body>

</html>
```
