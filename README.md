# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-22 00:33:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 12431.8 (3h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 187931
telemt_connections_bad_total 12733
telemt_connections_current 659
telemt_connections_me_current 659
telemt_handshake_timeouts_total 10675
telemt_upstream_connect_attempt_total 5077
telemt_upstream_connect_success_total 5076
telemt_upstream_connect_attempts_per_request{bucket="1"} 5076
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3184
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 175
telemt_me_reconnect_success_total 87
telemt_me_reader_eof_total 84
telemt_me_idle_close_by_peer_total 84
telemt_me_route_drop_no_conn_total 37204
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153551
telemt_me_endpoint_quarantine_total 84
telemt_me_single_endpoint_shadow_rotate_total 105
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 1128
telemt_desync_full_logged_total 319
telemt_desync_suppressed_total 809
telemt_desync_frames_bucket_total{bucket="1_2"} 302
telemt_desync_frames_bucket_total{bucket="3_10"} 385
telemt_desync_frames_bucket_total{bucket="gt_10"} 441
telemt_pool_swap_total 13
telemt_pool_force_close_total 351
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 4532
telemt_me_writer_removed_unexpected_total 84
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 340
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4264
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4181
telemt_me_writer_teardown_success_total{mode="normal"} 4604
telemt_me_writer_teardown_noop_total 4533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9137
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.676575
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9137
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 79
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 153319
telemt_user_connections_current{user="hello"} 659
telemt_user_octets_from_client{user="hello"} 1751214152 (1.63 GB)
telemt_user_octets_to_client{user="hello"} 53383573756 (49.72 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 25798.2 (7h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 696656
telemt_connections_bad_total 40191
telemt_connections_current 531
telemt_connections_me_current 531
telemt_handshake_timeouts_total 26430
telemt_upstream_connect_attempt_total 11137
telemt_upstream_connect_success_total 10944
telemt_upstream_connect_fail_total 174
telemt_upstream_connect_attempts_per_request{bucket="1"} 11118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 174
telemt_me_reconnect_attempts_total 995
telemt_me_reconnect_success_total 334
telemt_me_reader_eof_total 288
telemt_me_idle_close_by_peer_total 288
telemt_me_route_drop_no_conn_total 329738
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 562997
telemt_me_endpoint_quarantine_total 237
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 209
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 2455
telemt_desync_full_logged_total 1411
telemt_desync_suppressed_total 1044
telemt_desync_frames_bucket_total{bucket="1_2"} 526
telemt_desync_frames_bucket_total{bucket="3_10"} 919
telemt_desync_frames_bucket_total{bucket="gt_10"} 1010
telemt_pool_swap_total 28
telemt_pool_force_close_total 772
telemt_me_writer_close_signal_drop_total 58
telemt_me_draining_writers_reap_progress_total 9810
telemt_me_writer_removed_unexpected_total 271
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 858
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9227
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 765
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9038
telemt_me_writer_teardown_success_total{mode="normal"} 10085
telemt_me_writer_teardown_noop_total 9810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19895
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.397844
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19895
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 58
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 230
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 562168
telemt_user_connections_current{user="hello"} 531
telemt_user_octets_from_client{user="hello"} 9304504388 (8.67 GB)
telemt_user_octets_to_client{user="hello"} 198175310316 (184.57 GB)
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 100658.0 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7511268
telemt_connections_bad_total 605932
telemt_connections_current 1775
telemt_connections_me_current 1775
telemt_handshake_timeouts_total 244504
telemt_upstream_connect_attempt_total 36611
telemt_upstream_connect_success_total 36539
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 36546
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19825
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1502
telemt_me_reconnect_success_total 754
telemt_me_reader_eof_total 764
telemt_me_idle_close_by_peer_total 764
telemt_me_route_drop_no_conn_total 4507179
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6115495
telemt_me_endpoint_quarantine_total 635
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 748
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 25948
telemt_desync_full_logged_total 8583
telemt_desync_suppressed_total 17365
telemt_desync_frames_bucket_total{bucket="1_2"} 5582
telemt_desync_frames_bucket_total{bucket="3_10"} 10119
telemt_desync_frames_bucket_total{bucket="gt_10"} 10247
telemt_pool_swap_total 108
telemt_pool_force_close_total 3635
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 577
telemt_me_draining_writers_reap_progress_total 33384
telemt_me_writer_removed_unexpected_total 734
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2811
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30866
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3396
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29749
telemt_me_writer_teardown_success_total{mode="normal"} 33677
telemt_me_writer_teardown_noop_total 33428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67105
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 154.846276
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67105
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 577
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 674
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6107822
telemt_user_connections_current{user="hello"} 1775
telemt_user_octets_from_client{user="hello"} 104598977996 (97.42 GB)
telemt_user_octets_to_client{user="hello"} 2014112378760 (1.83 TB)
telemt_user_unique_ips_current{user="hello"} 868
telemt_user_unique_ips_recent_window{user="hello"} 279
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 100659.2 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6180114
telemt_connections_bad_total 580317
telemt_connections_current 1519
telemt_connections_me_current 1519
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 204477
telemt_upstream_connect_attempt_total 40768
telemt_upstream_connect_success_total 40387
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 40572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19618
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1852
telemt_me_reconnect_success_total 815
telemt_me_reader_eof_total 788
telemt_me_idle_close_by_peer_total 788
telemt_me_route_drop_no_conn_total 2199708
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4630059
telemt_me_endpoint_quarantine_total 618
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 769
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 22175
telemt_desync_full_logged_total 7513
telemt_desync_suppressed_total 14662
telemt_desync_frames_bucket_total{bucket="1_2"} 5344
telemt_desync_frames_bucket_total{bucket="3_10"} 8599
telemt_desync_frames_bucket_total{bucket="gt_10"} 8232
telemt_pool_swap_total 109
telemt_pool_force_close_total 3291
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 348
telemt_me_draining_writers_reap_progress_total 32073
telemt_me_writer_removed_unexpected_total 770
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2738
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30040
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28782
telemt_me_writer_teardown_success_total{mode="normal"} 32778
telemt_me_writer_teardown_noop_total 32079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64857
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.039354
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64857
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 348
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 711
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 4566967
telemt_user_connections_current{user="hello"} 1519
telemt_user_octets_from_client{user="hello"} 138576355125 (129.06 GB)
telemt_user_octets_to_client{user="hello"} 2143217651779 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 731
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 100623.4 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6085792
telemt_connections_bad_total 541221
telemt_connections_current 1268
telemt_connections_me_current 1268
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 195051
telemt_upstream_connect_attempt_total 47068
telemt_upstream_connect_success_total 46749
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 46884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21016
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 373
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1830
telemt_me_reconnect_success_total 843
telemt_me_reader_eof_total 784
telemt_me_idle_close_by_peer_total 784
telemt_me_route_drop_no_conn_total 2113018
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4541466
telemt_me_endpoint_quarantine_total 682
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 753
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 22049
telemt_desync_full_logged_total 7361
telemt_desync_suppressed_total 14688
telemt_desync_frames_bucket_total{bucket="1_2"} 5393
telemt_desync_frames_bucket_total{bucket="3_10"} 8444
telemt_desync_frames_bucket_total{bucket="gt_10"} 8212
telemt_pool_swap_total 108
telemt_pool_force_close_total 3173
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 33442
telemt_me_writer_removed_unexpected_total 754
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2790
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31415
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2958
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30269
telemt_me_writer_teardown_success_total{mode="normal"} 34205
telemt_me_writer_teardown_noop_total 33453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67658
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.549789
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67658
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 730
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4542387
telemt_user_connections_current{user="hello"} 1268
telemt_user_octets_from_client{user="hello"} 132107110019 (123.03 GB)
telemt_user_octets_to_client{user="hello"} 2079533720555 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 645
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 100662.7 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20076187
telemt_connections_bad_total 1507500
telemt_connections_current 2204
telemt_connections_me_current 2204
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 582949
telemt_upstream_connect_attempt_total 190034
telemt_upstream_connect_success_total 172371
telemt_upstream_connect_fail_total 16039
telemt_upstream_connect_attempts_per_request{bucket="1"} 188410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8889
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16039
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64374
telemt_me_reconnect_success_total 2178
telemt_me_reader_eof_total 1365
telemt_me_idle_close_by_peer_total 1364
telemt_me_route_drop_no_conn_total 39464319
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16316740
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 772
telemt_me_single_endpoint_outage_enter_total 123
telemt_me_single_endpoint_outage_exit_total 123
telemt_me_single_endpoint_outage_reconnect_attempt_total 259
telemt_me_single_endpoint_outage_reconnect_success_total 62
telemt_me_single_endpoint_quarantine_bypass_total 259
telemt_me_single_endpoint_shadow_rotate_total 784
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 31500
telemt_desync_full_logged_total 9382
telemt_desync_suppressed_total 22118
telemt_desync_frames_bucket_total{bucket="1_2"} 6847
telemt_desync_frames_bucket_total{bucket="3_10"} 13969
telemt_desync_frames_bucket_total{bucket="gt_10"} 10684
telemt_pool_swap_total 103
telemt_pool_force_close_total 3408
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 764
telemt_me_draining_writers_reap_progress_total 31290
telemt_me_writer_removed_unexpected_total 2024
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4262
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28788
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2889
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 519
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27882
telemt_me_writer_teardown_success_total{mode="normal"} 33050
telemt_me_writer_teardown_noop_total 31316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64366
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.379393
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64366
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 764
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1511
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 16444451
telemt_user_connections_current{user="hello"} 2204
telemt_user_octets_from_client{user="hello"} 193411770232 (180.13 GB)
telemt_user_octets_to_client{user="hello"} 1141517488110 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1000
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 100630.1 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5871225
telemt_connections_bad_total 552908
telemt_connections_current 1404
telemt_connections_me_current 1404
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 121664
telemt_upstream_connect_attempt_total 55203
telemt_upstream_connect_success_total 54573
telemt_upstream_connect_fail_total 538
telemt_upstream_connect_attempts_per_request{bucket="1"} 55111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32347
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21884
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 538
telemt_me_reconnect_attempts_total 68176
telemt_me_reconnect_success_total 1703
telemt_me_reader_eof_total 1482
telemt_me_idle_close_by_peer_total 1481
telemt_me_route_drop_no_conn_total 2365194
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4578003
telemt_me_endpoint_quarantine_total 672
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 754
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 23045
telemt_desync_full_logged_total 8079
telemt_desync_suppressed_total 14966
telemt_desync_frames_bucket_total{bucket="1_2"} 4369
telemt_desync_frames_bucket_total{bucket="3_10"} 8926
telemt_desync_frames_bucket_total{bucket="gt_10"} 9750
telemt_pool_swap_total 103
telemt_pool_force_close_total 3019
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 382
telemt_me_draining_writers_reap_progress_total 34817
telemt_me_writer_removed_unexpected_total 1527
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3676
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32692
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2618
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31798
telemt_me_writer_teardown_success_total{mode="normal"} 36368
telemt_me_writer_teardown_noop_total 34818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71186
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.993284
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71186
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 382
telemt_me_refill_failed_total 4122
telemt_me_writer_restored_same_endpoint_total 1435
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 4571045
telemt_user_connections_current{user="hello"} 1404
telemt_user_octets_from_client{user="hello"} 122603513424 (114.18 GB)
telemt_user_octets_to_client{user="hello"} 1868263139086 (1.70 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 37466.0 (10h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3748330
telemt_connections_bad_total 133369
telemt_connections_current 1289
telemt_connections_me_current 1289
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1550868
telemt_upstream_connect_attempt_total 23536
telemt_upstream_connect_success_total 23384
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 23529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7888
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_reconnect_attempts_total 45671
telemt_me_reconnect_success_total 905
telemt_me_reader_eof_total 581
telemt_me_idle_close_by_peer_total 581
telemt_me_route_drop_no_conn_total 1002039
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1819573
telemt_me_endpoint_quarantine_total 273
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 284
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10065
telemt_desync_full_logged_total 3454
telemt_desync_suppressed_total 6611
telemt_desync_frames_bucket_total{bucket="1_2"} 1777
telemt_desync_frames_bucket_total{bucket="3_10"} 3857
telemt_desync_frames_bucket_total{bucket="gt_10"} 4431
telemt_pool_swap_total 40
telemt_pool_force_close_total 1294
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 123
telemt_me_draining_writers_reap_progress_total 12907
telemt_me_writer_removed_unexpected_total 660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1348
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12240
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1088
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11613
telemt_me_writer_teardown_success_total{mode="normal"} 13588
telemt_me_writer_teardown_noop_total 12909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26497
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.218367
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26497
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 123
telemt_me_refill_failed_total 2601
telemt_me_writer_restored_same_endpoint_total 812
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1823315
telemt_user_connections_current{user="hello"} 1289
telemt_user_octets_from_client{user="hello"} 52933046480 (49.30 GB)
telemt_user_octets_to_client{user="hello"} 780348486178 (726.76 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 674
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 18436.8 (5h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168294
telemt_connections_bad_total 1413
telemt_connections_current 303
telemt_connections_me_current 303
telemt_handshake_timeouts_total 4592
telemt_upstream_connect_attempt_total 8572
telemt_upstream_connect_success_total 8552
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 8571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3674
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 176
telemt_me_reconnect_success_total 114
telemt_me_reader_eof_total 115
telemt_me_idle_close_by_peer_total 115
telemt_me_route_drop_no_conn_total 47007
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147852
telemt_me_endpoint_quarantine_total 178
telemt_me_single_endpoint_shadow_rotate_total 164
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 988
telemt_desync_full_logged_total 246
telemt_desync_suppressed_total 742
telemt_desync_frames_bucket_total{bucket="1_2"} 386
telemt_desync_frames_bucket_total{bucket="3_10"} 359
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 20
telemt_pool_force_close_total 459
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 7699
telemt_me_writer_removed_unexpected_total 112
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 509
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7305
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7240
telemt_me_writer_teardown_success_total{mode="normal"} 7814
telemt_me_writer_teardown_noop_total 7699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 15513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15513
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.818811
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15513
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 106
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 147566
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 2794605076 (2.60 GB)
telemt_user_octets_to_client{user="hello"} 85746196452 (79.86 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 100634.5 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7094849
telemt_connections_bad_total 719018
telemt_connections_current 1635
telemt_connections_me_current 1635
telemt_handshake_timeouts_total 202223
telemt_upstream_connect_attempt_total 38719
telemt_upstream_connect_success_total 38572
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 38682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19394
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 1513
telemt_me_reconnect_success_total 799
telemt_me_reader_eof_total 779
telemt_me_idle_close_by_peer_total 779
telemt_me_route_drop_no_conn_total 2103398
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5346186
telemt_me_endpoint_quarantine_total 693
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 772
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 20664
telemt_desync_full_logged_total 6908
telemt_desync_suppressed_total 13756
telemt_desync_frames_bucket_total{bucket="1_2"} 5030
telemt_desync_frames_bucket_total{bucket="3_10"} 7498
telemt_desync_frames_bucket_total{bucket="gt_10"} 8136
telemt_pool_swap_total 111
telemt_pool_force_close_total 3018
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 373
telemt_me_draining_writers_reap_progress_total 34852
telemt_me_writer_removed_unexpected_total 751
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2806
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32815
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2930
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31834
telemt_me_writer_teardown_success_total{mode="normal"} 35621
telemt_me_writer_teardown_noop_total 34854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70475
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.578433
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70475
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 373
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 713
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5321351
telemt_user_connections_current{user="hello"} 1635
telemt_user_octets_from_client{user="hello"} 108058579744 (100.64 GB)
telemt_user_octets_to_client{user="hello"} 2497718273320 (2.27 TB)
telemt_user_unique_ips_current{user="hello"} 747
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 100631.2 (27h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6088122
telemt_connections_bad_total 599223
telemt_connections_current 1618
telemt_connections_me_current 1618
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 168485
telemt_upstream_connect_attempt_total 54563
telemt_upstream_connect_success_total 54147
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 54504
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21062
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 5414
telemt_me_reconnect_success_total 1105
telemt_me_reader_eof_total 988
telemt_me_idle_close_by_peer_total 988
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2157483
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4718009
telemt_me_endpoint_quarantine_total 799
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 767
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 19446
telemt_desync_full_logged_total 6541
telemt_desync_suppressed_total 12905
telemt_desync_frames_bucket_total{bucket="1_2"} 4878
telemt_desync_frames_bucket_total{bucket="3_10"} 7074
telemt_desync_frames_bucket_total{bucket="gt_10"} 7494
telemt_pool_swap_total 109
telemt_pool_force_close_total 2981
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 33485
telemt_me_writer_removed_unexpected_total 999
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3290
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31240
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2758
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30504
telemt_me_writer_teardown_success_total{mode="normal"} 34530
telemt_me_writer_teardown_noop_total 33489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68019
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68019
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.952858
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68019
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 859
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 4721225
telemt_user_connections_current{user="hello"} 1618
telemt_user_octets_from_client{user="hello"} 89316619449 (83.18 GB)
telemt_user_octets_to_client{user="hello"} 2023884752532 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 712
telemt_user_unique_ips_recent_window{user="hello"} 156
```