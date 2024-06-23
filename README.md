
# Apache HTTP Server Command

## Installation of Apache

#### Step 1: Update package lists

```sh
sudo apt update
```
#### Step 2: Install Apache

```sh
sudo apt install apache2
```
#### Step 3: Allow through firewall

```sh
sudo ufw allow "Apache"
```
#### Step 4: Check Apache Status

```sh
sudo systemctl status apache2
```

## Basic Command of apache2 systemctl

#### Check Apache Status
```sh
sudo systemctl status apache2
```
#### Start Apache
```sh
sudo systemctl start apache2
```
#### Stop Apache
```sh
sudo systemctl stop apache2
```
#### Restart Apache
```sh
sudo systemctl restart apache2
```
#### Reload Apache Configuration
```sh
sudo systemctl reload apache2
```
#### Enable Apache to start on boot
```sh
sudo systemctl enable apache2
```
#### Disable Apache from starting on boot
```sh
sudo systemctl disable apache2
```
