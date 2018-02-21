TARGET=Textures.xbt

all: $(TARGET)

.PHONY: force

$(TARGET):
	/mnt/package/mediacenter-osmc/src/xbmc-a9a7a20071bfd759e72e7053cee92e6f5cfb5e48/tools/depends/native/TexturePacker/bin/TexturePacker -dupecheck -input . -output $(TARGET)

clean:
	rm -f $(TARGET)

distclean: clean

