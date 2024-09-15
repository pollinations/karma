# Chat with Pollinations.ai 🌟 React Components

This project showcases the integration of [Next.js](https://nextjs.org) with [Pollinations.ai](https://pollinations.ai) for creating generative content using React components.

## 🚀 Getting Started

![Generative Image](https://image.pollinations.ai/prompt/Visualize%20a%20natural%20scene%20inspired%20by%20the%20concept%20of%20'lotus'%2C%20featuring%20blooming%20lotus%20flowers%20that%20symbolize%20user%20growth.%20Interlace%20futuristic%20codes%20resembling%20the%20Matrix%20and%20TypeScript%2C%20flowing%20like%20a%20stream%20to%20represent%20the%20seamless%20integration%20of%20Next.js%20and%20Pollinations.ai.%20Include%20the%20text%20'karma.pollinations.ai'%20in%20a%20stylish%2C%20modern%20font%2C%20enhancing%20the%20atmosphere%20of%20creativity%20and%20technology.?width=768&height=768&model=flux&seed=18&nologo=true&enhance=false)

Follow these steps to get the project up and running:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/pollinations/karma
    cd karma
    ```

2. **Install dependencies**:

    Choose your preferred package manager:

    ```bash
    npm install    # or yarn install
    pnpm install   # or bun install
    ```

3. **Run the development server**:

    Start the development environment:

    ```bash
    npm run dev    # or yarn dev
    pnpm dev       # or bun dev
    ```

4. **View the project**:

    Open [http://localhost:3000](http://localhost:3000) in your browser to see the application running. You can start modifying the code by editing the `app/page.tsx` file. Changes are reflected automatically.

---

## 🧩 Pollinations.ai Components

Take advantage of Pollinations.ai to generate dynamic content with ease. Here are some examples of the available components:

### `PollinationsText`

This component generates and displays plain text based on a prompt and seed using the Pollinations API.

```javascript
import React from 'react';
import { PollinationsText } from '@pollinations/react';

const TermsAndConditions = () => (
  <PollinationsText seed={42}>
    Write out Pollinations.AI terms and conditions in Chinese.
  </PollinationsText>
);

export default TermsAndConditions;
```

### `PollinationsMarkdown`

Generates and displays markdown-formatted text from a prompt.

```javascript
import React from 'react';
import { PollinationsMarkdown } from '@pollinations/react';

const AdSlogan = () => (
  <PollinationsMarkdown seed={42}>
    Create a great advertising slogan with cool formatting about Pollinating in markdown.
  </PollinationsMarkdown>
);

export default AdSlogan;
```

### `PollinationsImage`

Generates and displays an image based on a text prompt and a seed.

```javascript
import React from 'react';
import { PollinationsImage } from '@pollinations/react';

const SunsetImage = () => (
  <PollinationsImage prompt="A beautiful sunset over the ocean" width={800} height={600} seed={42} />
);

export default SunsetImage;
```

---

## 💡 Learn More

- Check out [README](https://pollinations.ai/readme) / [KARMA.YT](https://karma.yt)

### Made with ❤️ by pollinations.ai