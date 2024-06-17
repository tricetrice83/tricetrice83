- 👋 Hi, I’m @tricetrice83
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
tricetrice83/tricetrice83 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
import "./styles.css";

document.getElementById("app").innerHTML = `
<h1>Hello JavaScript!</h1>
`;
user_attributes": [

  ],
  "sessions": [

  ],
  "subscriptions": [

  ],
  "identities": [

  ],
  "devices": [

  ],
  "contacts": [
    {
      "contact_value": "+124463",Calendar storage_com.android.providers.calendar_12.5.00.8_V1250000008.apkname: CI
on: [push]
jobs:
  build:
    name: Build, lint, and test on Node ${{ matrix.node }} and ${{ matrix.os }}

    runs-on: ${{ matrix.os }}
    strategy:
      matrix:
        node: ["16.x"]
        os: [ubuntu-latest, windows-latest, macOS-latest]

    steps:
      - name: Checkout repo
        uses: actions/checkout@v2

      - name: Use Node ${{ matrix.node }}
        uses: actions/setup-node@v1
        with:
          node-version: ${{ matrix.node }}

      - name: Install JS dependencies
        run: yarn install

      - name: Lint
        run: yarn lint

      - name: Build
        run: yarn

      - name: Test
        run: yarn test
      #   run: yarn test --ci --coverage --maxWorkers=2
