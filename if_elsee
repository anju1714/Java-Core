# Java-Core
Dive into the world of Java
Author : Anjali Shikare

package Assignment;

public class Assignment {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		        int[] sales = {5000, 1000, 6000, 7000, 1500, 20000, 3500, 4000};

		        // Initialize counters for each salary range
		        int[] salaryRanges = new int[9];

		        for (int sale : sales) {
		            int salary = calculateSalary(sale);

		            if (salary >= 200 && salary <= 299) {
		                salaryRanges[0]++;
		            } else if (salary >= 300 && salary <= 399) {
		                salaryRanges[1]++;
		            } else if (salary >= 400 && salary <= 499) {
		                salaryRanges[2]++;
		            } else if (salary >= 500 && salary <= 599) {
		                salaryRanges[3]++;
		            } else if (salary >= 600 && salary <= 699) {
		                salaryRanges[4]++;
		            } else if (salary >= 700 && salary <= 799) {
		                salaryRanges[5]++;
		            } else if (salary >= 800 && salary <= 899) {
		                salaryRanges[6]++;
		            } else if (salary >= 900 && salary <= 999) {
		                salaryRanges[7]++;
		            } else if (salary >= 1000) {
		                salaryRanges[8]++;
		            }
		        }

		        // Print the results
		        printSalaryRanges(salaryRanges);
		    }

		    public static int calculateSalary(int grossSales) {
		        return (int) (200 + 0.09 * grossSales);
		    }

		    public static void printSalaryRanges(int[] salaryRanges) {
		        String[] rangesLabels = {
		            "$200–299", "$300–399", "$400–499", "$500–599",
		            "$600–699", "$700–799", "$800–899", "$900–999", "$1000 and above"
		        };

		        for (int i = 0; i < salaryRanges.length; i++) {
		            System.out.println(rangesLabels[i] + ": " + salaryRanges[i]);
		        }
		    }
		}

	}

}
