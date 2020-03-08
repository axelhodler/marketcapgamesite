# marketcapgame.com page

Available at [marketcapgame.com](http://marketcapgame.com)

Images are pulled from the appstore

## Setup

```
bundle install
```

## Run

```
./bin/run.sh
```

## Setup with namecheap.com

namecheap -> manage domain -> Advanced DNS

Use the following [A records](https://help.github.com/en/github/working-with-github-pages/managing-a-custom-domain-for-your-github-pages-site)

```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

Plus a CNAME records pointing `www` to `akbits.github.io` (username or org)

Under the repo -> Settings -> Custom Domain (marketcapgame.com)
