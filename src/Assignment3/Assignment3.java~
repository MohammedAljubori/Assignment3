
package Assignment3;

import javax.swing.JOptionPane;
import java.util.Scanner;

public class Assignment3 {
	/**
	 * Purpose: To select an account type, and check for correct login
	 * credentials
	 * 
	 * @author Mohammed Aljubori 
	 * Algorithm: 
	 *         1. Prompt for a choice of an account type      
	 *         2. Prompt for username 
	 *         3. Authenticate username 
	 *         4. Prompt for password        
	 *         5. Authenticate password 
	 *         6. Welcome user
	 */
	public static void main(String[] args) {
		/**
		 * Initalized variables
		 */
		String StaffPass = "Staff";
		String AdminPass = "Admin";
		String StudentPass = "Student";
		String StaffUser = "Staff";
		String AdminUser = "Admin";
		String StudentUser = "Student";
		String entereduname;
		String enteredpass;
		int trials = 0;
		/**
		 * Prompt for account type
		 */
		Scanner keyboard = new Scanner(System.in);
		String[] choices = { "Staff", "Admin", "Student" };
		String input = (String) JOptionPane.showInputDialog(null,
				"Choose account type...", "Account Type",
				JOptionPane.QUESTION_MESSAGE, null, choices, choices[1]);

		

			switch (input) {

			case "Staff": {
				/**
				 * Staff username check
				 */
				while (trials < 3) {
					trials++;
					entereduname = JOptionPane
							.showInputDialog("Enter Username");
					if (!StaffUser.equals(entereduname) && trials < 3) {
						JOptionPane.showMessageDialog(null,
								"Incorrect Username");
						
					} else if (trials >= 3) {
						JOptionPane.showMessageDialog(null, "Contact Admin");

					} else
						/**
						 * Staff password check
						 */
						while (trials < 3) {
							trials++;
							enteredpass = JOptionPane
									.showInputDialog("Enter Password");
							if (!StaffPass.equals(enteredpass) && trials < 3) {
								JOptionPane.showMessageDialog(null,
										"Incorrect Password");
							} else if (trials >= 3) {
								JOptionPane.showMessageDialog(null,
										"Contact Admin");

							} else {
								JOptionPane.showMessageDialog(null, "Welcome "
										+ entereduname);
								trials=3;}
							break;
						}
				}
			}

			case "Admin": {
				/**
				 * Admin username check
				 */
				while (trials <= 3) {
					
					entereduname = JOptionPane
							.showInputDialog("Enter Username");
					if (!AdminUser.equals(entereduname) && trials < 3) {
						JOptionPane.showMessageDialog(null,
								"Incorrect Username");
						trials++;
						
					} else if (trials =3) {
						JOptionPane.showMessageDialog(null, "Contact Admin");

					} else
						/**
						 * admin password check
						 */
						while (trials <= 3) {
							
							enteredpass = JOptionPane
									.showInputDialog("Enter Password");
							if (!AdminPass.equals(enteredpass) && trials < 3) {
								JOptionPane.showMessageDialog(null,
										"Incorrect Password");
								trials++;
							} else if (trials = 3) {
								JOptionPane.showMessageDialog(null,
										"Contact Admin");

							} else{
								JOptionPane.showMessageDialog(null, "Welcome "
										+ entereduname);
								System.exit(0);}
							break;
						}
				}
			}
			case "Student": {
				/**
				 * student username check
				 */
				while (trials < 3) {
					trials++;
					entereduname = JOptionPane
							.showInputDialog("Enter Username");
					if (!StudentUser.equals(entereduname) && trials < 3) {
						JOptionPane.showMessageDialog(null,
								"Incorrect Username");
						
					} else if (trials >= 3) {
						JOptionPane.showMessageDialog(null, "Contact Admin");

					} else
						/**
						 * student password check
						 */
						while (trials < 3) {
							trials++;
							enteredpass = JOptionPane
									.showInputDialog("Enter Password");
							if (!StudentPass.equals(enteredpass) && trials < 3) {
								JOptionPane.showMessageDialog(null,
										"Incorrect Password");
							} else if (trials >= 3) {
								JOptionPane.showMessageDialog(null,
										"Contact Admin");

							} else
								{
								JOptionPane.showMessageDialog(null, "Welcome "
										+ entereduname);
								trials=3;
								}
							break;
						}
				}
			}
			
			}

		
	}
}
