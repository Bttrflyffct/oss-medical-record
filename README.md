[Medical Record Sharing](https://guide.blockchain.z.com/docs/oss/medical-record/) - GMO Blockchain Open Source
==================================================

License
--------------------------------------
License is [here](./LICENSE.txt).

Apart from forbidding the use of this software for criminal activity, this license is similar to the [MIT License](https://opensource.org/licenses/mit-license.php).

GMO Blockchain Open Source Common License document is [here](https://guide.blockchain.z.com/docs/oss/license/).

DEMO
--------------------------------------
You can check the operation of this sample project on this page.

http://oss.blockchain.z.com/medical-record/

Explanation
--------------------------------------
- #### GMO Blockchain Open Source
    http://guide.blockchain.z.com/docs/oss/

- #### Medical Record Sharing
    http://guide.blockchain.z.com/docs/oss/medical-record/

Usage Guides
--------------------------------------

### Create Z.com Cloud Blockchain environment
see [Setup Development Environment](https://guide.blockchain.z.com/docs/init/setup/)

### Install application
```bash
git clone https://github.com/zcom-cloud-blockchain/oss-medical-record.git
cd oss-medical-record
npm install
```
### Set up for deploy contracts
You need to set up [zcom-blockchain-cp](https://github.com/zcom-cloud-blockchain/zcom-blockchain-cp).

### Deploy contracts
```bash
cd oss-medical-record
truffle migrate
```


### Configure for client
Create public/js/config.json based on public/js/config_template.json. Edit "CNS", "ORGANIZATIONS_ADDRESS" and "HISTORIES_ADDRESS" which you deployed.


### Start application
```bash
node app.js
```
