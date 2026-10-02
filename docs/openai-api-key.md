# How to get an OpenAI API key

An API key is a secret code that lets GatorGrade authenticate with OpenAI.

1. Sign in or create an account at [OpenAI Platform][platform].
2. Open the [API keys page][keys]. If you use a class project, select the
   project your instructor tells you to use.
3. Click **Create new secret key**, give it a name such as `GatorGrade`,
   and create the key.
4. Copy the key and save it somewhere private. If you lose it, create a new
   key; you cannot view the full secret again later.
5. Follow the [GatorGrade setup instructions][setup] to save the key in
   `AUTO_HINT_KEY_ENV` on your computer.

Keep your key private. Do not put it in your assignment files or on GitHub.
API use can cost money; ask your instructor about access before paying.

For more help, see the [official OpenAI quickstart][quickstart].

[platform]: https://platform.openai.com/
[keys]: https://platform.openai.com/api-keys
[setup]: ../README.md#persistent-remote-api-key
[quickstart]: https://platform.openai.com/docs/quickstart
