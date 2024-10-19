 xval = {0,15,34,55,76,104,116}

yval = {13,21,29,36,37,24,7}

sum = 0;

L = 1;

product =1;

n = Length[xval]


For[i=1,i <=n,i++,
For[j=1,j<=n,j++,
If[i !=j,product = ((x- xval[[j]])/(xval[[i]]- xval[[j]])), product = 1];
L=L*product;
];
sum = L* yval[[i]] + sum; L=1

Expand[sum]
>
