# @insihts/node

## Installation

```shell
npm install @insihts/node
```

## Usage

```javascript
import insihts from '@insihts/node';

insihts.init({
  websiteId: '31238599-94ad-4bec-a265-f409ab07f075', // Your website id
});

insihts.track({ url: '/home' });
```

The properties you can send using the `.track` function are:

- hostname: Hostname of server
- language: Client language (eg. en-US)
- referrer: Page referrer
- screen: Screen dimensions (eg. 1920x1080)
- title: Page title
- url: Page url
- name: Event name (for custom events)
- data: Event data properties