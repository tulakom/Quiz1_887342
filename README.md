# Quiz1_887342

US_states = 

	{"Alabama" => "AL",
	"Alaska" => "AK",
	"Arizona" => "AZ",
	"Arkansas" => "AR",
	"California" => "CA",
	"Colorado" => "CO",
	"Connecticut" => "CT",
	"Delaware" => "DE",
	"District of Columbia" => "DC",
	"Florida" => "FL",
	"Georgia" => "GA",
	"Hawaii" => "HI",
	"Idaho" => "ID",
	"Illinois" => "IL",
	"Indiana" => "IN",
	"Iowa" => "IA",
	"Kansas" => "KS",
	"Kentucky" => "KY",
	"Louisiana" => "LA",
	"Maine" => "ME",
	"Maryland" => "MD",
	"Massachusetts" => "MA",
	"Michigan" => "MI",
	"Minnesota" => "MN",
	"Mississippi" => "MS",
	"Missouri" => "MO",
	"Montana" => "MT",
	"Nebraska" => "NE",
	"Nevada" => "NV",
	"New Hampshire" => "NH",
	"New Jersey" => "NJ",
	"New Mexico" => "NM",
	"New York" => "NY",
	"North Carolina" => "NC",
	"North Dakota" => "ND",
	"Ohio" => "OH",
	"Oklahoma" => "OK",
	"Oregon" => "OR",
	"Pennsylvania" => "PA",
	"Rhode Island" => "RI",
	"South Carolina" => "SC",
	"South Dakota" => "SD",
	"Tennessee" => "TN",
	"Texas" => "TX",
	"Utah" => "UT",
	"Vermont" => "VT",
	"Virginia" => "VA",
	"Washington" => "WA",
	"West Virginia" => "WV",
	"Wisconsin" => "WI",
	"Wyoming" => "WY"}
	
	
	1.1 US_states.each {|x ,y|
	
 	if "#{y[1]}"=="T" || "#{y[1]}"=="N"
 	    
	    puts "#{y}"
	end
	}
	
  1.2 puts US_states.sort.reverse
    
    
  1.3  US_states.each do | key, value|
	if (key[0] == "A"|| key[0] =="E"|| key[0] =="I"|| key[0] =="O"|| key[0] =="U") &&  
	    (key[key.length-1] == "a"||key[key.length-1] =="e"||key[key.length-1] =="i"||key[key.length-1] =="o"||key[key.length-1] =="u" )  
  puts  key
  
    
  end
  end
  
   
  2. require 'prime'
num = gets.chomp
n = 1
Prime.each(num.to_i) do |prime|
    print "p#{n} -> #{prime}, "
    n += 1
end

