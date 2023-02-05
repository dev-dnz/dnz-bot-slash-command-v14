# Installation
### Node.js 18.14.0 or newer is required.

#### npm install discord.js

#### npm install dotenv

# He can help you

👇👇👇👇👇👇👇👇

![flag-united-kingdom_1f1ec-1f1e7](https://user-images.githubusercontent.com/124462134/216839398-a716ed72-e25b-447d-bd70-c8cab3e8e47f.png) 

The definition of a slash command must have a name and a description. Slash command names must be between 1-32 characters and contain no capital letters, spaces, or symbols other than - and _. Using the builder, a simple ping command definition would look like this

```const { SlashCommandBuilder } = require('discord.js');

module.exports = {
	data: new SlashCommandBuilder()
		.setName('ping')
		.setDescription('Replies with Pong!'),
	async execute(interaction) {
		await interaction.reply('Pong!');
	},
};
```

![flag-romania_1f1f7-1f1f4](https://user-images.githubusercontent.com/124462134/216839474-ee044123-2a90-4e6c-8d4b-04c1dc436d7f.png)

Definiția unei comenzi slash trebuie să aibă un nume și o descriere. Numele comenzilor Slash trebuie să fie cuprinse între 1-32 de caractere și să nu conțină litere majuscule, spații sau simboluri, altele decât - și _. Folosind constructorul, un simplu ping definiția comenzii ar arăta astfel

```const { SlashCommandBuilder } = require('discord.js');

module.exports = {
	data: new SlashCommandBuilder()
		.setName('ping')
		.setDescription('Replies with Pong!'),
	async execute(interaction) {
		await interaction.reply('Pong!');
	},
};
```







