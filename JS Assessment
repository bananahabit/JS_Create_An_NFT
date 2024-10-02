/*
Assessment Requirements
1. Create a variable that can hold a number of NFT's. What type of variable might this be?
2. Create an object inside your mintNFT function that will hold the metadata for your NFTs. 
   The metadata values will be passed to the function as parameters. When the NFT is ready, 
   you will store it in the variable you created in step 1
3. Your listNFTs() function will print all of your NFTs metadata to the console (i.e. console.log("Name: " + someNFT.name))
4. For good measure, getTotalSupply() should return the number of NFT's you have created
*/

// create a variable to hold your NFT's

// this function will take in some values as parameters, create an
// NFT object using the parameters passed to it for its metadata, 
// and store it in the variable above.
const NFTArr = []
let counter = 0;

function mintNFT (_name, _hat, _teeth, _fur, _eyewear) {
    const NFT = {
        "name": _name, 
        "hat": _hat, 
        "teeth": _teeth,
        "fur": _fur,
        "eyewear": _eyewear 
    }
    NFTArr.push(NFT);
    console.log ("Congratulations for the minted: " + _name + "\n"); 
}

// create a "loop" that will go through an "array" of NFT's
// and print their metadata with console.log()
function listNFTs () {

    while (counter < NFTArr.length){
        console.log ("Details of NFT: \t" + NFTArr[counter].name); 
        console.log ("Name: \t" + NFTArr[counter].name); 
        console.log ("Hat: \t" + NFTArr[counter].hat); 
        console.log ("Teeth: \t" + NFTArr[counter].teeth); 
        console.log ("Fur: \t" + NFTArr[counter].fur);
        console.log ("Eyewear: \t" + NFTArr[counter].eyewear + "\n");  
        
        counter++; 
    }
}

// print the total number of NFTs we have minted to the console
function getTotalSupply() {
    console.log ("The total number of your NFTs: " + NFTArr.length); 
}


// call your functions below this line

mintNFT("Poppy", "drip", "gold", "blue", "shades"); 
mintNFT("Luffy", "casual", "bronze", "yellow", "eyeglasses"); 
mintNFT("Rick", "old-money", "silver", "black", "rounded-glasses"); 

listNFTs(); 
getTotalSupply(); 
