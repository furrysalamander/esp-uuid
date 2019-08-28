# esp-uuid #
#### ESP32 UUID4 Generator Library ####

This library generates RFC 4122 UUIDs.

Just include the header and you're good to go.

There are three functions in the library:


* StringUUIDGen()
  * Returns a String with a UUID in it.
* UUIDGen(char \*returnUUID)
  * Fills returnUUID with a UUID.  returnUUID should be at least 37 characters long. *Doesn't use strings.*
* IntToHex(const unsigned int inInt, char \*returnVar)
  * Used internally to generate a hex string from an integer.
