


gg.alert("🔥 Bear ~ ꜱᴀꜰᴇ ꜱᴄʀɪᴩᴛ 🔥")
gg.toast('coi chừng bị bế đi nhá 🤡')


function star()
    local menu = gg.choice({
        "✪Combo hành động",
        "✪Hành động khác",
        "✪Đổi Ngoại hình",
        "✪Check Ban id",
        "❌ ᴇxɪᴛ ❌"
    }, nil, os["date"](
    "🔥 Vui lòng chọn chức năng 🔥 \n Share by BEAR ZYY \n------------------------\n Hôm nay: Ngày %d Tháng %m Năm %Y \n Bây giờ: %H:%M"))


        if menu == nil then
       else
        if menu == 1 then combo() end
        if menu == 2 then emote() end
        if menu == 3 then look() end
        if menu == 4 then check() end
        if menu == 5 then exitScript() end
    end
end

function check()
gg.setVisible(false)

text = gg.prompt({
	"UID : ",
	},{
		"NULL",
		},{
			"text",
			})

check = gg.makeRequest("https://scromnyi.vercel.app/region/ban-info?uid="..text[1]).content
check = check:gsub("\\","__")

function Utf(d)
	return (d:gsub("__u(....)", function (b)
		return utf8.char(tonumber(b, 16))
	end))
end


Conv = Utf(check)


function getin4(a)
	return a:gsub("_"," ").." : " .. Conv:match("\""..a.."\":\"(.-)\"")
end

in4={

	ban_status = getin4("ban_status"),
	
	Owner = getin4("Owner"),
	
	nickname = getin4("nickname"),
	
	region = getin4("region"),
}

gg.alert([[

		CHECK UID : ]]..text[1]..[[
		
		
]]..in4.ban_status..[[


]]..in4.nickname..[[


]]..in4.region..[[


]],"")
end



--thoát
function exitScript()
    gg.toast("Exiting Script...")
    os.exit()
end




--menu hành động 
on = [[ON✅️]]
off = [[OFF❌️]]


hack0= off
hack1= off
hack2= off
look1= off
look2= off
look3= off
look4= off
look5= off
look6= off
look7= off
look8= off
look9= off






function combo()
your_choice = gg.choice({
     "Combo lv7 "..hack0.." ",
     "Combo Hd đôi "..hack1.." ",
     "Combo duy chuyển "..hack2.." ",
     "❌thoát❌"
    }, nil, os["date"](
    "🔥 Vui lòng chọn Hành động 🔥 \n 𝙨𝙘𝙧𝙞𝙥𝙩 𝙗𝙮 𝙕𝙔𝙔 \n------------------------\n Hôm nay: Ngày %d Tháng %m Năm %Y \n Bây giờ: %H:%M"))
if your_choice == nil then
while true do
if gg.isVisible() then
gg.setVisible(false)
combo()
end
end
end
if your_choice == 1 then
 if hack0 == off then 
    gg.clearResults()   
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000004", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909045001", gg.TYPE_DWORD)
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909043007", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909038012", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000005", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909040010", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▶■□□□□")
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000037", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909039011", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▶■■□□□")    
    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000060", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909035012", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▶■■■□□")
    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000076", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909041005", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▶■■■□□")
    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909033006", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909038010", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▶■■■■□")
    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909034014", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909033001", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▶■■■■■")
hack0 = on
else
gg.clearResults()   
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909045001", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000004", gg.TYPE_DWORD)
    gg.clearResults()   
    gg.toast("▶■□□□□")
    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909038012", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909043007", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909040010", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000005", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▷■■□□□")
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909039011", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000037", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909035012", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000060", gg.TYPE_DWORD)
    gg.toast("▶■■■□□")
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909041005", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000076", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▷■■■■□")
    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909038010", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909033006", gg.TYPE_DWORD)
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909033001", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909034014", gg.TYPE_DWORD)
    gg.clearResults()   
    gg.toast("▷■■■■■")
hack0 = off
end
end
if your_choice == 2 then
 if hack1 == off then
gg.clearResults()   
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000004", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909044006", gg.TYPE_DWORD)  
    gg.clearResults()   
    gg.toast("▷■□□□□")
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909043007", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909047002", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000005", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909048001", gg.TYPE_DWORD)
    gg.clearResults()        
    gg.toast("▷■■□□□")
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000037", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909045012", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000060", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909043013", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▷■■■□□")
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000076", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909043010", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909033006", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909042013", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▷■■■■□")
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909034014", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909047003", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▷■■■■■")
hack1 = on
else
gg.clearResults()   
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909044006", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000004", gg.TYPE_DWORD)
    gg.clearResults()   
    gg.toast("▷■□□□□")
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909047002", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909043007", gg.TYPE_DWORD)
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909048001", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000005", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▷■■□□□")
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909045012", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000037", gg.TYPE_DWORD)
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909043013", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000060", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▷■■■□□")
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909043010", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000076", gg.TYPE_DWORD)
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909042013", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909033006", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▷■■■■□")
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909047003", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909034014", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("▷■■■■■")
hack1 = off
end
end
if your_choice == 3 then
 if hack2 == off then
gg.clearResults()   
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000004", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909048002", gg.TYPE_DWORD)
    gg.clearResults()   
    gg.toast("Số 1 Đã Bật")
 
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909043007", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909040001", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 2 Đã Bật")
    
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000005", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909040008", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 3 Đã Bật")
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000037", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909047001", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 4 Đã Bật")
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000060", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909043009", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 5 Đã Bật")
    
gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909000076", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909038004", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 6 Đã Bật")
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909033006", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909045011", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 7 Đã Bật")
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909034014", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909046013", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 8 Đã Bật")
hack2 = on
else
gg.clearResults()   
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909048002909048002", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000004", gg.TYPE_DWORD)
    gg.clearResults()   
    gg.toast("Số 1 Đã Bật")
 
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909040001", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909043007", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 2 Đã Bật")
    
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909040008", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000005", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 3 Đã Bật")
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909047001", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000037", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 4 Đã Bật")
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909043009", gg.TYPE_DWORD)
    gg.getResults(10000000)
gg.editAll("909000060", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 5 Đã Bật")
    
gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909038004", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909000076", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 6 Đã Bật")
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909045011", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909033006", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 7 Đã Bật")
    
    gg.clearResults()    
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("909046013", gg.TYPE_DWORD)
    gg.getResults(10000000)
    gg.editAll("909034014", gg.TYPE_DWORD)
    gg.clearResults()    
    gg.toast("Số 8 Đã Bật")
hack2 = off
end
end
end
if your_choice == 4 then star() end
    gg.toast("Đang trở về...")


function look()
lookon = gg.choice({
     "Naruto "..look1.." ",
     "Cannibal Havoc "..look2.." ",
     "Devil Trigger Look Changer "..look3.." ",
     "Scorpio "..look4.." ",
     "Frostfire "..look5.." ",
     "Last Paradox "..look6.." ",
     "Aurora "..look7.." ",
     "Siêu hùng bóng đêm "..look8.." ",
     "Rampage "..look9.." ",
     "❌thoát❌"
    }, nil, os["date"](
    "🔥 Vui lòng chọn Hành động 🔥 \n 𝙨𝙘𝙧𝙞𝙥𝙩 𝙗𝙮 𝙕𝙔𝙔 \n------------------------\n Hôm nay: Ngày %d Tháng %m Năm %Y \n Bây giờ: %H:%M"))
if lookon == nil then
while true do
if gg.isVisible() then
gg.setVisible(false)
look()
end
end
end
if lookon == 1 then
 if look1 == off then
gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,047,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã bật✓  ")
look1 = on

else
gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,047,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã tắt✓  ")
look1 = off
end
end

if lookon == 2 then
 if look2 == off then
gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,000,003", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã bật✓  ")
look2 = on

else

gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,000,003", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã tắt✓  ")
look2 = off
end
end

if lookon == 3 then
 if look3 == off then
    gg.cleathenults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,038,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã bật✓  ")
  look3 = on
 else
 
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,038,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã tắt✓  ")
 look3 = off
  end
  end
  
  if lookon == 4 then
 if look4 == off then
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,039,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã bật✓  ")
  look4 = on
  else
  
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,039,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã tắt✓  ")
  look4 = off
  end 
  end
  
  if lookon == 5 then
 if look5 == off then
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,042,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã bật✓  ")
  look5 = on
  else
  
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,042,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã tắt✓  ")
 look5 = off
  end
  end
  if lookon == 6 then
 if look6 == off then
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,044,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã bật✓  ")
  look6 = on
  else
 
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,044,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã tắt✓  ")
  look6 = off
  end
  end
  
  if lookon == 7 then
 if look7 == off then
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,047,002", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã bật✓  ")
  look7 = on
  else

    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,047,002", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã tắt✓  ")
  look7 = off
  end
  end
  
  
  if lookon == 8 then
 if look8 == off then
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,048,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã bật✓  ")
  look8 = on
  else
  
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,048,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã tắt✓  ")
 look8 = off
  end
  end
  
  
  if lookon == 9 then
 if look9 == off then
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,000,002", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã bật✓  ")
  look9 = on
  else
  
    gg.clearResults()
    gg.setRanges(gg.REGION_ANONYMOUS)
    gg.searchNumber("914,000,002", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.getResults(100000, nil, nil, nil, nil, nil, nil, nil, nil)
    gg.editAll("914,000,001", gg.TYPE_DWORD, false, gg.SIGN_EQUAL, 0, -1, 0)
    gg.clearResults()
    gg.clearResults()
    gg.toast("✓Đã tắt✓  ")
 look9 = off
 end
 end
 
 if look == 10 then star() end
    gg.toast("Đang trở về...")
 
 
 
 
 
 
 
 
 
 

end
while true do
if gg.isVisible() then
gg.setVisible(false)
star()
end
end
