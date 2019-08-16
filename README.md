Reproduction of https://github.com/facebook/create-react-app/issues/7552

To reproduce the issue:

1. git clone https://github.com/klaaspieter/create-react-app-eslintrc.git
2. cd create-react-app-eslintrc
3. yarn (Note that yarn.lock changes, is this a separate issue?)
4. EXTEND_ESLINT=true yarn start
