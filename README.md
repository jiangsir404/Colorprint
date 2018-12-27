# Colorprint
用Python装饰器封装的一个实现logger+colorlog的颜色输出功能，不需要依赖第三方库

## usage

一共有两个类

Logger类:

	from colorprint import Logger
    logger = Logger()
    logger.info('test1')
    logger.error('test2')
    logger.debug('test3')
    logger.warning('test4')
    logger.critical('test5')
    logger.success('test6')


ColorPrint类

    colorprint = ColorPrint()
    colorprint.print_red_text('i am red')
    colorprint.print_random_text('i am change color')
    colorprint.print_random_text('i am change color')


![1.jpg](1.jpg)