### Requirements

- Node.js and npm

### Getting started

Run the following command on your local environment:

```
npm install
```

Then, you can run locally in development mode with live reload:

```
npm run dev
```

Open http://localhost:3000 with your favorite browser to see your project. For your information, Next JS need to take some time to compile the project for your first time.

```
.
├── README.md            # README file
├── next.config.js       # Next JS configuration
├── public               # Public folder
│   └── assets
│       └── images       # Image used by default template
├── src
│   ├── background       # Atomic background component
│   ├── button           # Atomic button component
│   ├── cta              # Atomic cta component
│   ├── feature          # Atomic feature component
│   ├── footer           # Atomic footer component
│   ├── hero             # Atomic hero component
│   ├── layout           # Atomic layout component
│   ├── navigation       # Atomic navigation component
│   ├── pages            # Next JS pages
│   ├── styles           # PostCSS style folder with Tailwind
│   ├── templates        # Default template
│   └── utils            # Utility folder
├── tailwind.config.js   # Tailwind CSS configuration
└── tsconfig.json        # TypeScript configuration
```

### Deploy to production

You can see the results locally in production mode with:

```
$ npm run build
$ npm run start
```

### License

Licensed under the MIT License, Copyright © 2024
