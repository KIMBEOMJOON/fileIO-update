# fileIO-update
for main i added

	int itemCount = 0; 
  
  //file.readFile(catalog); is now  
	itemCount = file.readFile(catalog);
    
    
  added to case 1
	itemCount = file.addMacBook(catalog, itemCount, tempValue);
	file.writeFile(catalog, itemCount);
  
  
  added to case 2
	itemCount = file.deleteMacBook(catalog, itemCount, tempValue);
	file.writeFile(catalog, itemCount);
