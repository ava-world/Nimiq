# phase 1

To join phase 1A all you have to do is generate a wallet and fill the registration form
follow this steps to generate your wallet using your vps or ubuntu on your local machine.

## step 1: upgrade your machine

<img src ="https://github.com/ava-world/Nimiq/blob/main/images/nimiq%201.1.png?raw=true" />

```
sudo apt upgrade && sudo apt update -y
```

<img src="https://github.com/ava-world/Nimiq/blob/main/images/nimiq%201.2.png?raw=true" />

<li> If you see an image asking"Y/N just type "Y" and click enter </li>

## step 2: Install Rust 1.73.0

```
rustup install 1.73.0
```

After successfully installing rust 1.73.0 jump to step 3

<li> If you enter an error like "command not found" it means you have to install rust, you can install rust with this command below </li>

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

<img src="https://github.com/ava-world/Nimiq/blob/main/images/nimiq%201.6.png?raw=true" />

<li>If you see any image like the one above just type "1" and continue with enter </li>

<img src="https://github.com/ava-world/Nimiq/blob/main/images/nimiq%201.7.png?raw=true" />

After downloading you should see an image like the one above

<li>Next step is to close your ubuntu/terminal/putty and restart it again so the path will be updated</li>

## step 3: Download the directory

<img src="https://github.com/ava-world/Nimiq/blob/main/images/nimiq%201.8.png?raw=true" />

```
git clone https://github.com/nimiq/snark-setup-operator.git
```

## step 4: Generate binary and wallet

```
cd snark-setup-operator
```

<img src="https://github.com/ava-world/Nimiq/blob/main/images/nimiq%201.9.png?raw=true" />

```
cargo build --release --bin generate
```

<img src="https://github.com/ava-world/Nimiq/blob/main/images/nimiq%201.10.png?raw=true" />


This should take some minutes, just leave it to run.


<li>ignore the warning and move to the next code </li>


![image](https://github.com/ava-world/Nimiq/assets/98952181/93dc95c6-8f65-409b-bb29-5e3cd19c3d10)

```
./target/release/generate
```

<img src="https://github.com/ava-world/Nimiq/blob/main/images/nimiq%201.12.png?raw=true" />


<li> use any moniker or just use your twitter username (lowercase no special character) and click enter </li>


<img src="https://github.com/ava-world/Nimiq/blob/main/images/nimiq%201.13.png?raw=true" />

<li> Type any character of better still use your twitter name again </li>

<img src="https://github.com/ava-world/Nimiq/blob/main/images/nimiq%201.14.png?raw=true" />

<li> Don't type anything here, just click enter </li> 

<li> Now copy your public key and your passphrase and save them securely </li>

You can now fill the below form  with your "public keys" generated

<p>https://docs.google.com/forms/d/e/1FAIpQLScHjdWS6x1C-RMXRyZHegP6V9wxliVuGB6M6mUI1bllgMTm5A/viewform?pli=1 </p>









