# Tyntec WhatsApp Slack API

Cloned from Tyntec's examples here: https://github.com/tyntec/api-samples

Some minor modifications:

- When closing a thread, do  `{ thread_ts: 'no thread assigned' }` instead of empty `thread_ts`
- Additional error logging with time to observe residual API invocations
- Some try / catches to show null object properties caused by pollers

## Installation

```bash
$ npm install
```

## Running the app

1. Create a `.env` file
2. Copy all the variables from `.env-example` to `.env`
3. Fill the variables with your own values
4. Run the server using the command below

```bash
$ npm start
```

