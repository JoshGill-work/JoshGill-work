- 👋 Hi, I’m @JoshGill-work
- 👀 I’m interested in learning how to use code to automate processes and improve data analysis.
- 🌱 I’m currently learning R & Python (in my spare time)
- 😄 Pronouns: he/they
- ⚡ Fun fact: i hate fun facts

<!---
JoshGill-work/JoshGill-work is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# Load in the data
raw_data <- read_csv("~/Downloads/25w26-AllMetrics.csv")

# Create the days of the Week as a list
levels =  c("Sun", "Mon", 
  "Tue", "Wed", "Thu", "Fri", "Sat")


raw_data$`Jnys-PY` <- as.numeric(raw_data$`Jnys-PY`)

This is my data, I want to run a Chi Square test to see if there is any significant difference between the observed results of this year (Jnys) vs last year (Jnys-PY) for each of the different ticket types in (TicketType) "Freedom Disabled" "Zip 16+"          "Freedom Elderly"  "60+"              "Bus & Tram Pass"  "Travelcard"       "CPC"              "Oyster PAYG"      "Zip Child"       
[10] "Veterans"        


I also need to only check for ModeGroup == "Bus"
