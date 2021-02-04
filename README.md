# wc-chat-client

This Repo was created to get a deeper understanding of Websockets and Custom Components.

# Phase 1

## What to build

1. A page with a headline and an input that asks for a Username and saves it.
2. A page that displays a window, an input and a submit button. The submitted inputs gets rendered in the window on submit.
3. Connect to a websocket and send and recieve simple text

## Websocket

1. Enable realtime communication between up to 4 clients.
2. Notify all users when someone enters or leaves the chat

## Custom component

1. Create a closed component that renders data recieved by the websocket
1. Make it possible to style it from the Outside
1. Should not change styles other than the elements it contains
1. The component should:
   - Recieve a websocket
   - A Username, which persists a page-reload
