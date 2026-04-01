
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
Fixed reconnect handling when the transport closes unexpectedly
Reduced duplicate session checks during polling
Fixed message ordering after a reconnect
Improved handling for empty polling responses
Removed an unnecessary transport state check
Fixed a reconnect edge case after receiving a close frame
Fixed session state after a transport fallback
Improved cleanup for completed polling requests
Fixed session state after a transport fallback
Improved cleanup for completed polling requests
Fixed cleanup when a session closes during an active poll
Fixed frame handling when a session reconnects mid-request
Simplified cleanup for stale transport state
Improved response handling after a polling timeout
Fixed duplicate message delivery after reconnect
Improved transport fallback when polling fails
Removed stale session data before reconnecting
Handled close frames received during an active request
Fixed session recovery when the transport reconnects too quickly
