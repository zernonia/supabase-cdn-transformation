<!-- PROJECT LOGO -->
<br />
<p align="center">
  <h3 align="center">Supabase Storage CDN & Transformation (Alternative Unofficial)</h3>

  <p align="center">
    Secured & Simple <strong><a href="https://supabase.io/">Supabase</a> Storage CDN & Transformation (Self-hosted).</strong>
    <br />
    <br />
    <a href="https://blog.zernonia.com/supabase-storage-cdn-and-transformation-with-serverless-function-unofficial">View Tutorial</a>
    ·
    <a href="https://github.com/zernonia/supabase-cdn-transformation/issues">Report Bug</a>
    ·
    <a href="https://github.com/zernonia/supabase-cdn-transformation/issues">Request Feature</a>
  </p>

  <p align="center">
    <a href="https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fzernonia%2Fsupabase-cdn-transformation&env=SUPABASE_URL&project-name=supabase-cdn-transformation&repo-name=supabase-cdn-transformation&demo-title=Supabase%20CDN%20Transformation&demo-description=Temporary%20Altnernative%20for%20Supabase%20Storage%20CDN%20%26%20Transformation&demo-url=https%3A%2F%2Fsupabase-cdn-transformation.vercel.app%2F&demo-image=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1631296527320%2FTH24GsjXyv.png%3Fw%3D1600%26h%3D840%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress"><img src="https://vercel.com/button" alt="Deploy with Vercel"/></a>
  </p>
</p>

![Supabase CDN & Transformation](https://cdn.hashnode.com/res/hashnode/image/upload/v1631296527320/TH24GsjXyv.png?w=1600&h=840&fit=crop&crop=entropy&auto=compress)

## 🚀 Features

- ☁ CDN
- 🤚 Image Transformation (width, height, quality)
- 🚀 1-Click Deploy!
- 🔒 Hosted on your own Vercel instance
- 👀 No Sensitive info required

## 📇 Inspiration/Showcase

I had a website called [Made With Supabase](https://www.madewithsupabase.com/), which showcase projects that made with Supabase. A problem occurs to me where the images load super-duper slow. Hence, I started to look into this issue.

It turns out that some of the images has around 5MB 🤯, which is too high quality, and wasting data quota as well for all my visitors!

Then, I found out that [Supabase Storage](https://supabase.io/storage)'s CDN and Transformation still Working in Progress. I don't want to wait any longer, and thus, I've created this simple **Serverless CDN and Image Transformation** service for everyone! 🎇✨🎉.

### 🔨 Built With

- [Vercel](https://vercel.com/)

## 🐾 Instructions

1. Click [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fzernonia%2Fsupabase-cdn-transformation&env=SUPABASE_URL&project-name=supabase-cdn-transformation&repo-name=supabase-cdn-transformation&demo-title=Supabase%20CDN%20Transformation&demo-description=Temporary%20Altnernative%20for%20Supabase%20Storage%20CDN%20%26%20Transformation&demo-url=https%3A%2F%2Fsupabase-cdn-transformation.vercel.app%2F&demo-image=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1631296527320%2FTH24GsjXyv.png%3Fw%3D1600%26h%3D840%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress)
2. Create a new Git repo.
3. Create a team? You can `skip` it.
4. Key in `SUPABASE_URL` (only support 1 project at once) in the Environment Variables.
5. Wait for deployment
6. Congratulations! Your serverless function is up and running! Enjoy !!! 🎉
7. 🌟 this repo, 🐤 this project, ☕ buy me a coffee?
8. Learn more from this [Blog post](https://blog.zernonia.com/supabase-storage-cdn-and-transformation-with-serverless-function-unofficial).

## How to use

Here are some of the parameter to pass along the new image's url.

```sh
w: width          (number of pixel)    // optional
h: height         (number of pixel)    // optional
f: file_name      (eg: avatar.png)
b: bucket_name    (eg: static)
q: quality        (0 to 100)           // optional

```

1. Click `Deploy` button above and follow the instruction above.
2. Wrap all the images url in your project's `<img>` with the following code. <br>
   `https://{ url-for-the-serverless-function-you-just-deployed }/api/resize?...`
3. Pass the parameter into the url as query string. (eg:) <br>
   `https://.../api/resize?f=avatar.png&b=static&w=1200`
4. Insert the link into `<img src="here" >` and you are done!

<!--
## ➕ Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request -->

<!-- ## 🙏 Acknowledgement

1. Fundamental for this Visualization ([Generate database types from OpenAPI specification](https://supabase.io/docs/reference/javascript/generating-types#generate-database-types-from-openapi-specification))
2. Guide to Construct Dynamic SVG Connector ([Connecting Table using SVG](https://codepen.io/alojzije/pen/ndfrI))
3. [Icones - icon gallery](https://icones.js.org/) -->

<!-- ## 📈 Analytics

I'm using [Umami Analytics](https://umami.is/docs/about) because I'm interested in the distributions of user who uses Supabase and this tool.

[This](https://umami-zernonia.vercel.app/share/yzSUulXQ/Supabase%20Schema) is the public URL for the analytics. Enjoy! -->

## 📜 License

Not Associated with Supabase.

Distributed under the MIT License. See `LICENSE` for more information.

# 📧 Contact

Twitter - [@zernonia](https://twitter.com/zernonia)

Also, if you like my work, please buy me a coffee ☕😳

<a href="https://www.buymeacoffee.com/zernonia" target="_blank">
    <img src="https://www.buymeacoffee.com/assets/img/custom_images/yellow_img.png" alt="Logo" >
  </a>
