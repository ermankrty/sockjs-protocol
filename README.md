
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
Simplified frame cleanup after a failed poll
Fixed a session timeout edge case during reconnect
Fixed message buffering when the connection drops mid-send
Improved cleanup for abandoned polling sessions
Simplified transport selection after reconnect
Fixed reconnect behavior when the previous session is still closing
Reduced duplicate transport checks during initialization
Fixed a case where reconnect attempts continued after session closure
Fixed frame delivery after a delayed reconnect
Improved cleanup for expired transport sessions
Fixed a case where heartbeat timers were not cleared after disconnect
Fixed duplicate heartbeat scheduling after reconnect
Improved handling for responses received after session close
Simplified transport cleanup when reconnect attempts fail
Fixed session recovery when polling resumes after a pause
Improved frame handling when multiple messages arrive together
Removed an unnecessary reconnect state transition
Fixed a case where pending frames were not cleared after disconnect
Fixed session cleanup when a transport closes before initialization finishes
Improved handling for duplicate open frames
Fixed reconnect handling when a session expires between polls
Improved frame validation for malformed payloads
Removed duplicate cleanup during transport fallback
Handled delayed responses after a session has already closed
Fixed a case where session cleanup ran twice after disconnect
Fixed a case where retry state was not cleared after reconnect
Improved handling for messages queued during transport changes
Fixed a case where queued messages remained after session reset
Fixed a case where transport state was not reset after a failed reconnect
Improved handling when a polling request finishes after session closure
Fixed cleanup for frames left queued during reconnect
Fixed a reconnect edge case when the previous transport had not fully closed
Improved message delivery after switching transports
Removed stale retry metadata during session reset
Fixed message cleanup after a failed transport switch
Fixed session recovery after a dropped polling connection
Simplified cleanup for completed transport retries
Fixed a case where reconnect state persisted after session reset
Fixed session recovery after an interrupted reconnect
Improved message handling while transport state is changing
Removed stale polling state after disconnect
Fixed a case where reconnect timers continued after session shutdown
Fixed message delivery when a transport reconnects with pending data
Simplified session teardown after transport errors
Fixed a case where transport errors left stale session state
Fixed session state after a transport retry succeeds
Improved cleanup for stale polling callbacks
Fixed duplicate close handling during reconnect
Improved transport recovery after a failed poll
Fixed a case where transport state was not cleared after a failed handshake
Fixed session recovery when a reconnect starts before the previous poll finishes
Improved validation for malformed transport responses
Removed stale callbacks after session replacement
Fixed queued message handling after transport recovery
Fixed transport fallback when the preferred connection closes early
Improved session cleanup after a failed handshake retry
Handled duplicate messages received during reconnect
Simplified transport selection for recovered sessions
Fixed pending frame cleanup after a session timeout
Fixed a case where session state persisted after a transport timeout
Fixed session recovery when reconnect starts during pending cleanup
Improved handling for duplicate transport callbacks
Simplified frame cleanup after session replacement
Fixed session cleanup when reconnect fails midway
Improved handling for delayed transport callbacks
Removed duplicate checks from session recovery
Fixed queued frame delivery after transport reset
Fixed a race condition while switching transports
Improved handling for stale session callbacks
Simplified reconnect cleanup after a timeout
Fixed session recovery after an interrupted heartbeat
Improved cleanup for transport state left behind after retry
Fixed a case where reconnect state was not cleared after a heartbeat failure
Fixed duplicate reconnect attempts after transport failure
Improved frame delivery when switching transports
Removed stale session callbacks after reconnect
Fixed heartbeat scheduling after a failed poll
Simplified cleanup for replaced transport sessions
Fixed session cleanup when a retry completes after disconnect
Improved handling for frames queued during reconnect
Removed stale transport metadata after session replacement
Fixed message ordering when reconnect completes during an active poll
Improved validation for unexpected session responses
Removed duplicate cleanup from the polling error path
