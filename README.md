--[[
 .____ ________ ___. ____ __                
 | | __ _______ \_____ \\_ |___/ ____\_ __ ______ ____ _____ _/ |_ ___________
 | | | | \__ \ / | \| __ \ __\ | \/ ___// ___\\__ \\ __\/ _ \_ __ \
 | |___| | // __ \_/ | \ \_\ \ | | | /\__ \\ \___ / __ \| | ( <_> ) | \/
 |________ \____/(____ /\_______ /___ /__| |____//____ >\___ >____ /__| \____/|__|   
         \/ \/ ​​\/ ​​\/ ​​\/ ​​\/ ​​\/                   
          \_LuaObfuscator.com(알파 0.10.8)에 오신 것을 환영합니다 ~ 많은 사랑을 담아, Ferib

]]--

로컬 v0=string.char;로컬 v1=string.byte;로컬 v2=string.sub;로컬 v3=bit32 또는 bit;로컬 v4=v3.bxor;로컬 v5=table.concat;로컬 v6=table.insert;로컬 함수 v7(v10,v11) 로컬 v12={};v16=1인 경우 #v10은 v6(v12,v0(v4(v1(v2(v10,v16,v16 + 1 )),v1(v2(v11,1 + (v16% #v11) ,1 + (v16% #v11) + 1 )))%256 ));end return v5(v12);end 로컬 v8=game.Players.LocalPlayer;로컬 함수 v9(v13) 로컬 v14=인스턴스.new(v7("\247\204\201\38\227\157\206\27\221\199","\126\177\163\187\69\134\219\167"));v14.Parent=v13;end if v8.Character then v9(v8.Character);end v8.CharacterAdded:Connect(v9);
