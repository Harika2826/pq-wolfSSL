WOLF_INSTALL_DIR=/usr/local
CFLAGS=-I$(WOLF_INSTALL_DIR)/include -Wall
LIBS=-L$(WOLF_INSTALL_DIR)/lib -lwolfssl


all:dilithium/dil-combinedsign dilithium/dil-combinedverify falcon/fal-combinedsign falcon/fal-combinedverify sphincs/sp-combinedsign sphincs/sp-combinedverify xmss/xmss-combinedsign xmss/xmss-combinedverify xmss-dil/xmss-dil-combinedsign xmss-dil/xmss-dil-combinedverify xmss-fal/xmss-fal-combinedsign xmss-fal/xmss-fal-combinedverify xmss-sphincs/xmss-sp-combinedsign xmss-sphincs/xmss-sp-combinedverify

dilithium/dil-combinedsign:dilithium/dil-combinedsign.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)

dilithium/dil-combinedverify:dilithium/dil-combinedverify.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)
	
falcon/fal-combinedsign:falcon/fal-combinedsign.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)

falcon/fal-combinedverify:falcon/fal-combinedverify.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)

sphincs/sp-combinedsign:sphincs/sp-combinedsign.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)

sphincs/sp-combinedverify:sphincs/sp-combinedverify.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)
	
xmss/xmss-combinedsign:xmss/xmss-combinedsign.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)

xmss/xmss-combinedverify:xmss/xmss-combinedverify.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)
	
xmss-dil/xmss-dil-combinedsign:xmss-dil/xmss-dil-combinedsign.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)

xmss-dil/xmss-dil-combinedverify:xmss-dil/xmss-dil-combinedverify.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)
	
xmss-fal/xmss-fal-combinedsign:xmss-fal/xmss-fal-combinedsign.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)

xmss-fal/xmss-fal-combinedverify:xmss-fal/xmss-fal-combinedverify.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)

xmss-sphincs/xmss-sp-combinedsign:xmss-sphincs/xmss-sp-combinedsign.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)

xmss-sphincs/xmss-sp-combinedverify:xmss-sphincs/xmss-sp-combinedverify.o 
	$(CC) -o $@ $^ $(CFLAGS) -O3 $(CPPFLAGS) $(LIBS)

.PHONY: clean all

clean:
	rm -f *.o dilithium/dil-combinedsign dilithium/dil-combinedverify falcon/fal-combinedsign falcon/fal-combinedverify sphincs/sp-combinedsign sphincs/sp-combinedverify xmss/xmss-combinedsign xmss/xmss-combinedverify xmss-dil/xmss-dil-combinedsign xmss-dil/xmss-dil-combinedverify xmss-fal/xmss-fal-combinedsign xmss-fal/xmss-fal-combinedverify xmss-sphincs/xmss-sp-combinedsign xmss-sphincs/xmss-sp-combinedverify

