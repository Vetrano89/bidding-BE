# TPL Code Sample (Backend)

#### Be sure you have these versions of Node and NPM or the application won't work:

```
Node: >=10.16.0 <=14.x.x
NPM: ^6.0.0
```

#### How to run the app

```
git clone https://github.com/Vetrano89/tpl-code-sample-BE.git
cd tpl-code-sample-BE
yarn install
strapi develop
```

Ensure the app is running on http://localhost:1337/ otherwise it won't work with the Front End project (localhost:1337 is hard coded)

There should be partied pre-generated.  Check http://localhost:1337/admin/plugins/content-manager/collectionType/application::party.party to ensure these parties exist.

##### No parties showing in the database?

If the parties don't exist for some reason when you check the Strapi dashboard, you'll need to create them.

1. Click the `+ Add New Parties`
2. Enter a `name` and `businessName` for the party
3. Click `Save`
4. Click `Publish`.

Do this at least twice so you have have at least two parties to work with.
