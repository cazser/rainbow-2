<script>
	let name = 'world';
</script>

<div class="rainbow">
	<div>
		<div>
			<div>
				<div>
					<div>
						<div>
							<div>
								
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
	
</div>

<style>
	*{box-sizing: border-box;}
	
	.rainbow > div{
		width: 400px;
		height: 200px;
		overflow: hidden;
	}
	
	.rainbow >div >div{
		border: 1px solid ;
		height: 380px;
		margin: 10px;
		background: hsl(60, 50%, 50%);
		border-radius: 50%;
	}
	
	.rainbow >div >div >div{
		border: 1px solid ;
		height: 360px;
		margin: 10px;
		background: hsl(120, 50%, 50%);
		border-radius: 50%;
	}
	
	.rainbow >div >div >div >div {
		border: 1px solid ;
		height: 340px;
		margin: 10px;
		background: hsl(180, 50%, 50%);
		border-radius: 50%;
	}
	
	.rainbow >div >div >div >div >div {
		border: 1px solid ;
		height: 320px;
		margin: 10px;
		background: hsl(240, 50%, 50%);
		border-radius: 50%;
	}
	
	.rainbow >div >div >div >div >div >div {
		border: 1px solid ;
		height: 300px;
		margin: 10px;
		background: hsl(300, 50%, 50%);
		border-radius: 50%;
	}
	
	.rainbow >div >div >div >div >div >div >div {
		border: 1px solid ;
		height: 280px;
		margin: 10px;
		background:white;
		border-radius: 50%;
	}
</style>