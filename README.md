# Sample Laravel App for Multipart Uploads Using Laravel, AWS S3, and Uppy

This is a simple app built to demonstrate the use of the [laravel-uppy-s3-multipart-upload package](https://github.com/TappNetwork/laravel-uppy-s3-multipart-upload). It's a fresh default Laravel installation (latest version) and the default package installation.

## Installation

Clone the repository
```
git clone https://github.com/andreia/laravel-uppy-upload-app.git
```

Go to the app directory
```
cd laravel-uppy-upload-app
```

Install dependencies
```
composer install
```

Create an environment file
```
cp .env.example .env
```

Generate a new application key (sets the APP_KEY value in your `.env` file).
```
php artisan key:generate
```

Edit the `.env` file and add your AWS credentials
```
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_DEFAULT_REGION=
AWS_BUCKET=
```

Install JS libraries
```
npm install
```

Run all Mix tasks
```
npm run dev
```

You're all set!

## Question?

If you have any question please contact me on andreiabohner at gmail.com or on https://github.com/andreia/laravel-uppy-upload-app/discussions

## Screenshots

![Home - uploading file](/screenshots/home1.png)
![Home - uploaded file](/screenshots/home2.png)
