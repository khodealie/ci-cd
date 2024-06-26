# Use the latest LTS version of Node
FROM node:20

# Set the working directory in the container
WORKDIR /ganache

# Install Ganache CLI globally
RUN npm install -g ganache-cli

# Expose the port Ganache CLI will run on
EXPOSE 8545

# Command to run Ganache CLI
CMD ["ganache-cli", "-d", "--db", "/ganache/data", "--mnemonic", "myth like bonus scare over problem client lizard pioneer submit female collect"]
