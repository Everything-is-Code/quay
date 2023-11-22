# Install ODF, NOOBA and Quay


```
oc apply -k  ./bootstrap

appproject.argoproj.io/quay created
applicationset.argoproj.io/quay created
```

## Create Account in Quay

After all the componnents are installed and Argo is in sync
### First get url of the registry 
```
oc get Route


```

### Creating Account

proceed to create new Account in Quay 

![image](https://github.com/Everything-is-Code/quay/assets/10425803/c8993689-3e43-4589-bf85-ca1bbf819946)

Complate the fields

![image](https://github.com/Everything-is-Code/quay/assets/10425803/73d12e27-e648-469c-b6b8-7134d5faf718)

 ### we will generate an empty public repository

1.- Go to Create new Reposiroty
![image](https://github.com/Everything-is-Code/quay/assets/10425803/e0d90015-7190-4606-8d71-0335afb0e49b)

2.- complate the requere fields and select publuc , after summit 

![image](https://github.com/Everything-is-Code/quay/assets/10425803/b048003a-3269-463e-93f2-159cadfcfa45)

3.- Verify results

![image](https://github.com/Everything-is-Code/quay/assets/10425803/51e4b26f-94a9-4551-b779-5115014a04d6)

### Creating Robot Accoutn Account for Pipeline 

In the left Menu Go to Settings icon 

![image](https://github.com/Everything-is-Code/quay/assets/10425803/857b0cd6-5523-442c-a3c7-d3f0f00c7975)

In the  User and Robot Permissions section wi will click on dropdown manu and select Create Robbot Account

![image](https://github.com/Everything-is-Code/quay/assets/10425803/f7c5273a-a154-474b-87dd-2e5ce4f40a0c)

Complate fields and create

After assing write permissons and Add

![image](https://github.com/Everything-is-Code/quay/assets/10425803/9f3804d3-5814-47d6-9b1d-93460df503ab)





