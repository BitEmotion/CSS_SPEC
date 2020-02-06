### VisualFormatingmModel

문서를 처리하거나 시각 매체에서 나타내는데 사용되는 알고리즘

1. BOX생성 
	display 값에 의존하여 생성된다.
	display값은 display model에 정의된 속성으로 결정된다.

	A block-level element is visually formatted as a block (e.g., paragraph), intended to be vertically stacked.

	Block Level 
		Block level element 예시
		 1. block태그 2. list-item태그 3. table태그
		 Each Block level element generate a least one block-level box called the principal block level box

		1. Block level 요소는 수직으로 쌓인다.
		2. Block level 요소는 BFC에 속한다.

			Block Box
				1. Block level box
					Block level box는 자신의 부모들과 형제와의 행동  ex)Table태그
				2. Block container box
					Block container box은 자신의 후계자(자식, 자식의 자식, 손자...)와의 상호작용
				3. Anonymous block-level box
				4. Anonymous block box
				
	Inline Level