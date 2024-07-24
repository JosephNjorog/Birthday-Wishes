# 🎉 Happy Birthday 🎉

Welcome to the ultimate birthday celebration toolkit! This project is designed to add some extra sparkle to your loved one's special day with a customizable, fun-filled birthday page. 🎂🎈

## Project Overview

This project includes:

- A dynamic **birthday greeting** page that plays a special birthday song.
- Customizable sections to make your message as personal and creative as possible.
- Fun animations and a delightful design to make the birthday experience unforgettable.

## Project Structure

Here's a quick look at the project's structure:

```
.
├── .gitignore
├── LICENSE
├── README.md
├── customize.json
├── img/
│   ├── Love21.png
│   ├── ballon1.svg
│   ├── ballon2.svg
│   ├── ballon3.svg
│   ├── favicon.png
│   └── hat.svg
├── index.html
├── package-lock.json
├── package.json
├── script/
│   └── main.js
├── src/
│   └── audio/
│       └── Simi Happy Birthday Ft Adekunle Gold Deja Lyrics.mp3
└── style/
    └── style.css
```

## Getting Started

### 1. Cloning the Repository

Start by cloning this repository to your local machine:

```bash
git clone https://github.com/JosephNjorog/Birthday-Wishes
cd happy-birthday-party
```

### 2. Installing Dependencies

Install the necessary dependencies using npm:

```bash
npm install
```

### 3. Customizing the Greeting

To make this birthday greeting truly special, you'll want to customize a few things. Here's how you can do it:

#### **Editing the Message**

Open `index.html` and locate the following section:

```html
<p class="idea-1" data-node-name="text2">That's what I was going to do.</p>
<p class="idea-2" data-node-name="text3">But then I stopped.</p>
<p class="idea-3">
  <span data-node-name="text4">I realized, I wanted to do something</span>
  <strong data-node-name="text4Adjective">special</strong>.
</p>
<p class="idea-4" data-node-name="text5Entry">Because,</p>
<p class="idea-5">
  <span data-node-name="text5Content">You are Special</span>
  <span class="smiley" data-node-name="smiley">:)</span>
</p>
```

Feel free to replace these lines with your own personalized messages. Whether you want to express heartfelt sentiments or add a dash of humor, make it yours!

#### **Customizing the Audio**

To change the audio file for the birthday song, replace the `Simi Happy Birthday Ft Adekunle Gold Deja Lyrics.mp3` file in `src/audio/` with your preferred audio file. Make sure to name it the same as the existing file, or update the `index.html` file to reflect the new file name.

#### **Changing Images**

Replace the images in the `img/` folder with your own. For example, if you want a different background or a new hat, just update `Love21.png` or `hat.svg` with your own files. Ensure the new images have the same names or adjust the HTML accordingly.

#### **Styling Adjustments**

To tweak the appearance of your birthday greeting, edit `style/style.css`. This is where you can play around with colors, fonts, and layouts to fit your theme.

## Running the Project

To view your customized birthday greeting, simply open `index.html` in your web browser. For a more advanced setup, you can use a local server like [http-server](https://www.npmjs.com/package/http-server):

```bash
npx http-server
```

Navigate to `http://localhost:8080` in your browser to see your creation in action!

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contributing

Feel free to fork the repository and make improvements. If you come up with a great idea or fix a bug, submit a pull request!

## Contact

For any questions or support, you can reach me at [Email](mailto:njorojoe11173@gmail.com).

---

**Happy customizing and have a blast celebrating!** 🎉 If you need more inspiration or have any funny stories to share about your birthday page, don't hesitate to reach out! 😄

