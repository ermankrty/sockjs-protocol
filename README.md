
Fixed handshake handling when session data is missing
Improved fallback behavior for unsupported transports
Removed duplicate frame validation
Handled malformed close frames without breaking the session
Simplified session cleanup after disconnect
Fixed a timeout edge case during session startup
Fixed frame parsing when payload length is missing
Improved cleanup for sessions closed during reconnect
Fixed heartbeat handling after a brief connection drop
Fixed session recovery after an interrupted transport switch
Simplified validation for incoming message frames
Improved cleanup when a polling request is cancelled
