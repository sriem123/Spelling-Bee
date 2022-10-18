# Spelling-Bee
/**
 * Plays the NYT Spelling Bee.
 *
 * @author J. Hollingsworth and Sonith Riem
 */

public class Main {
    public static void main(String[] args) {

        SpellingBee bee = new SpellingBee();

        bee.promptForPuzzle();

        System.out.println(bee);

        bee.searchForAnswers();

        bee.displayAnswers();

    }

}
