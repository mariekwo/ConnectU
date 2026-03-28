size_t hashFunction(const std::strings& s, size_t m, size_t base =31){
	size_t h =0;
for(unsigned char c:s) {
	h=(h*b+c)%m);
}
Return h;
}

put(string key, User* user) {
    idx = hashFunction();
    HashNode* newNode = new HashNode();
    newNode->next = table[]
    table[] = newNode;
}

get(string key) {
    idx = hashFunction();
    HashNode* current = table[];

    while(current != nullptr) {
        if(current->==key) return current->value;
        current = current->next;
    }
    return nullptr;
}