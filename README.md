# Installation

1. CD into working directory.

   ```bash
   cd react-app
   ```

2. Run this command in root directory. Note: this command executes the `eslint-prettier-config.sh` bash script.

   ```bash
   exec 3<&1;bash <&3 <(curl https://raw.githubusercontent.com/hyhong-code/eslint-prettier-airbnb-react/master/eslint-prettier-config.sh 2> /dev/null)
   ```
