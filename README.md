# mqtt-cryptbridge
End-to-end encrypted bridge for non-secure MQTT communications


# Hybrid encryption
Uses symmetric Fernet encryption with the key crypted in RSA for long payloads. For shorter ones, it uses RSA directly.
