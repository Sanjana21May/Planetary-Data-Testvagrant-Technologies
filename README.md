# Planetary-Data-Testvagrant-Technologies
#Name: Sanjana Kumari 
#College: Women's Institute of Technology Darbhanga 
#Year of passing: 2021 
#Phone No: 6201320367 
#Mail Id:- sanjansingh95075@gmail.com




public class planet { String planet_name; String surface_gasses; int moon; String ring; public void Mercury(String planet_name,String surface_gasses,int moon,String ring){ this.planet_name=planet_name; this.surface_gasses=surface_gasses; this.moon=moon; this.ring=ring; } public void Venus(String planet_name,String surface_gasses1,String surface_gasses2,int moon,String ring){ this.planet_name=planet_name; this.surface_gasses=surface_gasses1; this.surface_gasses=surface_gasses2; this.moon=moon; this.ring=ring; } public void Earth(String planet_name,String surface_gasses1,String surface_gasses2,int moon,String ring){ this.planet_name=planet_name; this.surface_gasses=surface_gasses1; this.surface_gasses=surface_gasses2; this.moon=moon; this.ring=ring; } public void Jupitor(String planet_name,String surface_gasses1,String surface_gasses2,int moon,String ring){ this.planet_name=planet_name; this.surface_gasses=surface_gasses1; this.surface_gasses=surface_gasses2; this.moon=moon; this.ring=ring; } public void Saturn(String planet_name,String surface_gasses1,String surface_gasses2,int moon,String ring){ this.planet_name=planet_name; this.surface_gasses=surface_gasses1; this.surface_gasses=surface_gasses2; this.moon=moon; this.ring=ring; } public void Uranus(String planet_name,String surface_gasses1,String surface_gasses2,String surface_gasses3,int moon,String ring){ this.planet_name=planet_name; this.surface_gasses=surface_gasses1; this.surface_gasses=surface_gasses2; this.surface_gasses=surface_gasses3; this.moon=moon; this.ring=ring; }

public static void main(String[] args) {

    planet pl=new planet();
    pl.Mercury("Mercury ","null ",0," No");
    pl.Venus("Venus "," Carbon Dioxide"," Nitrogen ",0," No");
    pl.Earth("Earth ","nitrogen ","Oxygen",1,"No");
    pl.Jupitor("Jupitor ","Hydrogen", "Helium ",79," Yes");
    pl.Saturn("Saturn ","Hydrogen"," Helium ",83," Yes");
    pl.Uranus("Uranus ","Hydrogen", "Helium", "Methane ",27," Yes");




}
}
