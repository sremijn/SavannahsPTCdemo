<script>
	import Answer from "../components/answer.svelte";
	import Question from "../components/question.svelte";
import Score from "../components/score.svelte"
</script>
<Score score={14} />
<Question number={1}
answer1="First answer"
answer2="Second answer"
answer3= "Third answer"
answer4= "All of the above">
    This is my new question 
</Question>
