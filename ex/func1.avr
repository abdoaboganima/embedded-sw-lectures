	.file	"func1.c"
__SP_H__ = 0x3e
__SP_L__ = 0x3d
__SREG__ = 0x3f
__tmp_reg__ = 0
__zero_reg__ = 1
	.text
.global	func1
	.type	func1, @function
func1:
	push r28
	push r29
	push __zero_reg__
	in r28,__SP_L__
	in r29,__SP_H__
/* prologue: function */
/* frame size = 1 */
/* stack size = 3 */
.L__stack_usage = 3
	std Y+1,r24
	ldd r24,Y+1
	subi r24,lo8(-(55))
/* epilogue start */
	pop __tmp_reg__
	pop r29
	pop r28
	ret
	.size	func1, .-func1
	.ident	"GCC: (GNU) 5.4.0"
