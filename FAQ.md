<!-- 
@ author: Kobe Norris (KobeNorrisWu@gmail.com)
@ date: 2021/03/24 18/32/22 pm
@ 
 -->

# **FAQ**

1. <code>Game Board</code> 结构

    * <code>Game Board</code>
        * <code>piece</code> 1
            * <code>block</code> 1-1
            * <code>block</code> 1-2
            * <code>block</code> 1-3
            * <code>block</code> 1-4
        * <code>piece</code> 2
            * <code>block</code> 2-1
            * <code>block</code> 2-2
            * <code>block</code> 2-3
            * <code>block</code> 2-4
        * <code>piece</code> 3
            * <code>block</code> 3-1
            * <code>block</code> 3-2
            * <code>block</code> 3-3
            * <code>block</code> 3-4
        * ....

2. <code>piece</code> 结构
    * <code>piece</code>
        * rowPos
        * colPos
        * style
            * top
            * left
        * <code>block</code> 1-1
        * <code>block</code> 1-2
        * <code>block</code> 1-3
        * <code>block</code> 1-4


3. <code>block</code> 结构
    * <code>block</code> 1-1
        * style
            * top
            * left
            * width
            * height
            * background

4. game 运行流程
    1. <code>play()</code>

    2. <code>cleanBoard()</code>

    3. Gaming

        1. <code>generatePiece()</code>

            1. <code>initializePiece()</code>

        2. Manipulation

            1. <code>moveLeft(piece)</code>

            2. <code>moveRight(piece)</code>

            3. <code>rotateClock(piece)</code>

            4. <code>rotateAntiClock(piece)</code>

        3. <code>pieceMoveDown()</code>

            1. <code>check()</code>

            2. <code>rowFull(rowIdx)</code>

            3. <code>clearRow(rowIdx)</code>

            4. <code>rowDown(rowIdx)</code>

            5. <code>gameOver();</code>

    4. <code>gameOver()</code>