# gitpump


![alt gitpump](https://raw.githubusercontent.com/alclient/gitpump/main/Untitled.png)


gitpump 💊

gitpump on pump.fun

https://pump.fun/


``` // ༼ つ ◕_◕ ༽つ PUMP Gitpump Chat
// ----------------------------------
// * Updates instantly
// * Multiplayer
// * Works offline

import { pump,sol } from "@instantdb/solana";

const db = init({ 
  ca: ,
});

function Chat() {
  // 1. Read
  const { isLoading, error, data } = db.useQuery({
    messages: {},
  });

  // 2. Write
  const addMessage = (message) => {
    db.transact(tx.messages[id()].update(message));
  };

  // 3. Render!
  return <UI data={data} onAdd={addMessage} />;
}
``` 
