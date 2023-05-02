# **Shikigami no Shiro - Boss Explosion Sound Fix**

This patch fixes the explosion sound effects, that can be heard at the end of most boss fights in this game. The default boss explosion sound effects are quite loud overall, and they also have an extremely loud high-pitched noise running through them. The patch addresses both of these issues, without affecting any of the other sound effects in the game.

Note that this patch is for the Steam version (also called "Castle of Shikigami"), not the earlier PC release of the game.

## Patching Instructions:

1 - From the installed Shikigami no Shiro folder (the one where Shikigami.exe is), go to \data.

2 - Using your xdelta patcher of choice, apply the shiki1-besf.xdelta patch to the file named "pack1.pack". Make sure that your patched file has the same filename as the original.
  
##### NOTE 1: Keeping a backup of both the original and patched pack1.pack is a good idea, so they can be switched out whenever. But also because Steam at some point, might randomly decide, to revert the patched file back to the original state.

##### NOTE 2: The patching process can be verified with the hashes below:
  
pack1.pack

(Original) &nbsp; CRC32:&nbsp; a7460c6e  
(Original) &nbsp; MD5:  &nbsp; &nbsp;   0dc2be75584bf8b32cb04fd28e4b1ac8  
(Original) &nbsp; SHA-1: &nbsp; 09be431326f6761134d4a4d6474d4a96addb3dc8  
  
(Patched) &nbsp; CRC32:&nbsp; 1ac7c325  
(Patched) &nbsp; MD5:  &nbsp; &nbsp;   10b5798278adb50f7d58c5564fb623c3  
(Patched) &nbsp;  SHA-1: &nbsp; 28a81a2f9bc00acb6e870dc2736f003b130d8f7c  
