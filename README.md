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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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
- Оплачен до: 25 марта
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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
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

# Server Metrics 2026-03-21 11:13:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 52653.2 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1585101
telemt_connections_bad_total 79382
telemt_connections_current 1589
telemt_connections_me_current 1589
telemt_handshake_timeouts_total 63338
telemt_upstream_connect_attempt_total 20620
telemt_upstream_connect_success_total 20514
telemt_upstream_connect_fail_total 68
telemt_upstream_connect_attempts_per_request{bucket="1"} 20582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13120
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 26
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 1037
telemt_me_reconnect_success_total 452
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_route_drop_no_conn_total 942306
telemt_me_route_drop_channel_closed_total 360
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1215713
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 371
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 419
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 4941
telemt_desync_full_logged_total 1734
telemt_desync_suppressed_total 3207
telemt_desync_frames_bucket_total{bucket="1_2"} 1035
telemt_desync_frames_bucket_total{bucket="3_10"} 1908
telemt_desync_frames_bucket_total{bucket="gt_10"} 1998
telemt_pool_swap_total 57
telemt_pool_force_close_total 1669
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 297
telemt_me_draining_writers_reap_progress_total 18433
telemt_me_writer_removed_unexpected_total 426
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1507
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17213
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1608
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16764
telemt_me_writer_teardown_success_total{mode="normal"} 18720
telemt_me_writer_teardown_noop_total 18437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37157
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 119.625849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37157
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 297
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 395
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 1214795
telemt_user_connections_current{user="hello"} 1589
telemt_user_octets_from_client{user="hello"} 16964542475 (15.80 GB)
telemt_user_octets_to_client{user="hello"} 336047830531 (312.97 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 544.1 (0h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70754
telemt_connections_bad_total 2761
telemt_connections_current 3942
telemt_connections_me_current 3942
telemt_handshake_timeouts_total 2063
telemt_upstream_connect_attempt_total 202
telemt_upstream_connect_success_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 201
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_route_drop_no_conn_total 55317
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 62361
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 7
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
telemt_me_writers_active_current 45
telemt_desync_total 196
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 129
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 64
telemt_desync_frames_bucket_total{bucket="gt_10"} 82
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 116
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 115
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 115
telemt_me_writer_teardown_success_total{mode="normal"} 116
telemt_me_writer_teardown_noop_total 116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 232
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.034402
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 232
telemt_user_connections_total{user="hello"} 62347
telemt_user_connections_current{user="hello"} 3942
telemt_user_octets_from_client{user="hello"} 673791300 (642.58 MB)
telemt_user_octets_to_client{user="hello"} 10798113100 (10.06 GB)
telemt_user_unique_ips_current{user="hello"} 1807
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 52651.0 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3019092
telemt_connections_bad_total 329363
telemt_connections_current 3973
telemt_connections_me_current 3973
telemt_handshake_timeouts_total 109222
telemt_upstream_connect_attempt_total 20122
telemt_upstream_connect_success_total 20109
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 20110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 686
telemt_me_reconnect_success_total 382
telemt_me_reader_eof_total 393
telemt_me_idle_close_by_peer_total 393
telemt_me_route_drop_no_conn_total 1300520
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2400543
telemt_me_endpoint_quarantine_total 347
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 411
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 10483
telemt_desync_full_logged_total 3549
telemt_desync_suppressed_total 6934
telemt_desync_frames_bucket_total{bucket="1_2"} 2183
telemt_desync_frames_bucket_total{bucket="3_10"} 4126
telemt_desync_frames_bucket_total{bucket="gt_10"} 4174
telemt_pool_swap_total 57
telemt_pool_force_close_total 1743
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 241
telemt_me_draining_writers_reap_progress_total 18316
telemt_me_writer_removed_unexpected_total 370
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1507
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17039
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 13
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1650
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16573
telemt_me_writer_teardown_success_total{mode="normal"} 18546
telemt_me_writer_teardown_noop_total 18329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36875
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.034967
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36875
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 241
telemt_me_refill_failed_total 15
telemt_me_writer_restored_same_endpoint_total 338
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 2397134
telemt_user_connections_current{user="hello"} 3973
telemt_user_octets_from_client{user="hello"} 39179742560 (36.49 GB)
telemt_user_octets_to_client{user="hello"} 880150855804 (819.70 GB)
telemt_user_unique_ips_current{user="hello"} 1436
telemt_user_unique_ips_recent_window{user="hello"} 589
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 52652.6 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2500902
telemt_connections_bad_total 279190
telemt_connections_current 3393
telemt_connections_me_current 3393
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 104358
telemt_upstream_connect_attempt_total 25097
telemt_upstream_connect_success_total 24843
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 24973
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13098
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11295
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1064
telemt_me_reconnect_success_total 493
telemt_me_reader_eof_total 452
telemt_me_idle_close_by_peer_total 452
telemt_me_route_drop_no_conn_total 727957
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1761285
telemt_me_endpoint_quarantine_total 358
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 409
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_me_writers_active_current 47
telemt_desync_total 8092
telemt_desync_full_logged_total 2767
telemt_desync_suppressed_total 5325
telemt_desync_frames_bucket_total{bucket="1_2"} 2012
telemt_desync_frames_bucket_total{bucket="3_10"} 3163
telemt_desync_frames_bucket_total{bucket="gt_10"} 2917
telemt_pool_swap_total 57
telemt_pool_force_close_total 1572
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 18132
telemt_me_writer_removed_unexpected_total 444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1512
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17080
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 98
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16560
telemt_me_writer_teardown_success_total{mode="normal"} 18592
telemt_me_writer_teardown_noop_total 18133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36725
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.869330
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36725
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 413
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1762853
telemt_user_connections_current{user="hello"} 3393
telemt_user_octets_from_client{user="hello"} 33736807165 (31.42 GB)
telemt_user_octets_to_client{user="hello"} 846382807519 (788.26 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1339
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 52616.1 (14h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2440145
telemt_connections_bad_total 274865
telemt_connections_current 3534
telemt_connections_me_current 3534
telemt_handshake_timeouts_total 72402
telemt_upstream_connect_attempt_total 21479
telemt_upstream_connect_success_total 21425
telemt_upstream_connect_attempts_per_request{bucket="1"} 21425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 780
telemt_me_reconnect_success_total 527
telemt_me_reader_eof_total 468
telemt_me_idle_close_by_peer_total 468
telemt_me_route_drop_no_conn_total 708942
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1754589
telemt_me_endpoint_quarantine_total 408
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 402
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 8238
telemt_desync_full_logged_total 2802
telemt_desync_suppressed_total 5436
telemt_desync_frames_bucket_total{bucket="1_2"} 2190
telemt_desync_frames_bucket_total{bucket="3_10"} 3135
telemt_desync_frames_bucket_total{bucket="gt_10"} 2913
telemt_pool_swap_total 56
telemt_pool_force_close_total 1551
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 159
telemt_me_draining_writers_reap_progress_total 19252
telemt_me_writer_removed_unexpected_total 444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1527
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18201
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1436
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 115
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17701
telemt_me_writer_teardown_success_total{mode="normal"} 19728
telemt_me_writer_teardown_noop_total 19255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38983
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.378381
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38983
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 159
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 454
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1751859
telemt_user_connections_current{user="hello"} 3534
telemt_user_octets_from_client{user="hello"} 40087633776 (37.33 GB)
telemt_user_octets_to_client{user="hello"} 854442424732 (795.76 GB)
telemt_user_unique_ips_current{user="hello"} 1270
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 52655.4 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7688715
telemt_connections_bad_total 510048
telemt_connections_current 4968
telemt_connections_me_current 4968
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 273357
telemt_upstream_connect_attempt_total 63464
telemt_upstream_connect_success_total 59769
telemt_upstream_connect_fail_total 2943
telemt_upstream_connect_attempts_per_request{bucket="1"} 62712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42010
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2364
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2943
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 3159
telemt_me_reconnect_success_total 1087
telemt_me_reader_eof_total 784
telemt_me_idle_close_by_peer_total 783
telemt_me_route_drop_no_conn_total 13232370
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6412603
telemt_me_endpoint_quarantine_total 414
telemt_me_single_endpoint_outage_enter_total 58
telemt_me_single_endpoint_outage_exit_total 58
telemt_me_single_endpoint_outage_reconnect_attempt_total 121
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 121
telemt_me_single_endpoint_shadow_rotate_total 415
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
telemt_desync_total 12273
telemt_desync_full_logged_total 3929
telemt_desync_suppressed_total 8344
telemt_desync_frames_bucket_total{bucket="1_2"} 2670
telemt_desync_frames_bucket_total{bucket="3_10"} 5395
telemt_desync_frames_bucket_total{bucket="gt_10"} 4208
telemt_pool_swap_total 53
telemt_pool_force_close_total 1661
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 341
telemt_me_draining_writers_reap_progress_total 17655
telemt_me_writer_removed_unexpected_total 1050
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2272
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16329
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1416
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15994
telemt_me_writer_teardown_success_total{mode="normal"} 18601
telemt_me_writer_teardown_noop_total 17664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36265
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.428300
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36265
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 341
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 763
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 6448423
telemt_user_connections_current{user="hello"} 4968
telemt_user_octets_from_client{user="hello"} 54514228972 (50.77 GB)
telemt_user_octets_to_client{user="hello"} 632024303563 (588.62 GB)
telemt_user_msgs_from_client{user="hello"} 129175
telemt_user_msgs_to_client{user="hello"} 449473
telemt_user_unique_ips_current{user="hello"} 1847
telemt_user_unique_ips_recent_window{user="hello"} 1067
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 52623.3 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2439229
telemt_connections_bad_total 288627
telemt_connections_current 3607
telemt_connections_me_current 3607
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 52404
telemt_upstream_connect_attempt_total 22911
telemt_upstream_connect_success_total 22672
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 22886
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11709
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 47
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_reconnect_attempts_total 2206
telemt_me_reconnect_success_total 743
telemt_me_reader_eof_total 739
telemt_me_idle_close_by_peer_total 739
telemt_me_route_drop_no_conn_total 834912
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1851099
telemt_me_endpoint_quarantine_total 337
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 407
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 8568
telemt_desync_full_logged_total 3091
telemt_desync_suppressed_total 5477
telemt_desync_frames_bucket_total{bucket="1_2"} 1649
telemt_desync_frames_bucket_total{bucket="3_10"} 3459
telemt_desync_frames_bucket_total{bucket="gt_10"} 3460
telemt_pool_swap_total 54
telemt_pool_force_close_total 1482
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 127
telemt_me_draining_writers_reap_progress_total 19057
telemt_me_writer_removed_unexpected_total 716
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18008
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1334
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 148
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17575
telemt_me_writer_teardown_success_total{mode="normal"} 19796
telemt_me_writer_teardown_noop_total 19057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38494
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38853
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.894366
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38853
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 127
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 624
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 1836780
telemt_user_connections_current{user="hello"} 3607
telemt_user_octets_from_client{user="hello"} 33608809624 (31.30 GB)
telemt_user_octets_to_client{user="hello"} 829587773462 (772.61 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1374
telemt_user_unique_ips_recent_window{user="hello"} 568
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 52617.5 (14h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3600837
telemt_connections_bad_total 190971
telemt_connections_current 3588
telemt_connections_me_current 3588
telemt_handshake_timeouts_total 1537009
telemt_upstream_connect_attempt_total 21396
telemt_upstream_connect_success_total 21362
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 21365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11471
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 752
telemt_me_reconnect_success_total 385
telemt_me_reader_eof_total 383
telemt_me_idle_close_by_peer_total 383
telemt_me_route_drop_no_conn_total 680780
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1646870
telemt_me_endpoint_quarantine_total 403
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 416
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_me_writers_active_current 83
telemt_desync_total 8024
telemt_desync_full_logged_total 2872
telemt_desync_suppressed_total 5152
telemt_desync_frames_bucket_total{bucket="1_2"} 1453
telemt_desync_frames_bucket_total{bucket="3_10"} 3189
telemt_desync_frames_bucket_total{bucket="gt_10"} 3382
telemt_pool_swap_total 57
telemt_pool_force_close_total 1407
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 19094
telemt_me_writer_removed_unexpected_total 371
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1280
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18206
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1386
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17687
telemt_me_writer_teardown_success_total{mode="normal"} 19486
telemt_me_writer_teardown_noop_total 19094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38580
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.032899
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38580
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 337
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1642115
telemt_user_connections_current{user="hello"} 3588
telemt_user_octets_from_client{user="hello"} 29289075908 (27.28 GB)
telemt_user_octets_to_client{user="hello"} 797510721120 (742.74 GB)
telemt_user_unique_ips_current{user="hello"} 1488
telemt_user_unique_ips_recent_window{user="hello"} 479
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 50608.9 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737424
telemt_connections_bad_total 28280
telemt_connections_current 519
telemt_connections_me_current 519
telemt_handshake_timeouts_total 274132
telemt_upstream_connect_attempt_total 24430
telemt_upstream_connect_success_total 24428
telemt_upstream_connect_attempts_per_request{bucket="1"} 24428
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10116
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14249
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1067
telemt_me_reconnect_success_total 401
telemt_me_reader_eof_total 396
telemt_me_idle_close_by_peer_total 396
telemt_me_route_drop_no_conn_total 156815
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374342
telemt_me_endpoint_quarantine_total 478
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 431
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_writers_active_current 43
telemt_desync_total 2501
telemt_desync_full_logged_total 972
telemt_desync_suppressed_total 1529
telemt_desync_frames_bucket_total{bucket="1_2"} 405
telemt_desync_frames_bucket_total{bucket="3_10"} 899
telemt_desync_frames_bucket_total{bucket="gt_10"} 1197
telemt_pool_swap_total 56
telemt_pool_force_close_total 1242
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 84
telemt_me_draining_writers_reap_progress_total 21880
telemt_me_writer_removed_unexpected_total 377
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1600
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20661
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20638
telemt_me_writer_teardown_success_total{mode="normal"} 22261
telemt_me_writer_teardown_noop_total 21880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44141
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.454037
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44141
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 84
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 323
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 374431
telemt_user_connections_current{user="hello"} 519
telemt_user_octets_from_client{user="hello"} 5468162747 (5.09 GB)
telemt_user_octets_to_client{user="hello"} 144794812445 (134.85 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 52627.4 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2595317
telemt_connections_bad_total 242457
telemt_connections_current 4185
telemt_connections_me_current 4185
telemt_handshake_timeouts_total 62235
telemt_upstream_connect_attempt_total 22282
telemt_upstream_connect_success_total 22188
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 22252
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11075
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 918
telemt_me_reconnect_success_total 502
telemt_me_reader_eof_total 468
telemt_me_idle_close_by_peer_total 468
telemt_me_route_drop_no_conn_total 686355
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2053158
telemt_me_endpoint_quarantine_total 416
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 415
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 8119
telemt_desync_full_logged_total 2704
telemt_desync_suppressed_total 5415
telemt_desync_frames_bucket_total{bucket="1_2"} 1968
telemt_desync_frames_bucket_total{bucket="3_10"} 3040
telemt_desync_frames_bucket_total{bucket="gt_10"} 3111
telemt_pool_swap_total 58
telemt_pool_force_close_total 1450
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 150
telemt_me_draining_writers_reap_progress_total 20041
telemt_me_writer_removed_unexpected_total 460
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1528
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18989
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1426
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18591
telemt_me_writer_teardown_success_total{mode="normal"} 20517
telemt_me_writer_teardown_noop_total 20041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40558
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.367506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40558
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 150
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 447
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 8
telemt_user_connections_total{user="hello"} 2046946
telemt_user_connections_current{user="hello"} 4185
telemt_user_octets_from_client{user="hello"} 43515415364 (40.53 GB)
telemt_user_octets_to_client{user="hello"} 960175890188 (894.23 GB)
telemt_user_unique_ips_current{user="hello"} 1514
telemt_user_unique_ips_recent_window{user="hello"} 647
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 52624.2 (14h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2375963
telemt_connections_bad_total 187896
telemt_connections_current 3950
telemt_connections_me_current 3950
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 59864
telemt_upstream_connect_attempt_total 38409
telemt_upstream_connect_success_total 38177
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 38366
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12711
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 581
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_reconnect_attempts_total 3155
telemt_me_reconnect_success_total 651
telemt_me_reader_eof_total 569
telemt_me_idle_close_by_peer_total 569
telemt_me_seq_mismatch_total 27
telemt_me_route_drop_no_conn_total 691397
telemt_me_route_drop_channel_closed_total 49
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1921275
telemt_me_endpoint_quarantine_total 460
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 411
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 7238
telemt_desync_full_logged_total 2468
telemt_desync_suppressed_total 4770
telemt_desync_frames_bucket_total{bucket="1_2"} 1897
telemt_desync_frames_bucket_total{bucket="3_10"} 2688
telemt_desync_frames_bucket_total{bucket="gt_10"} 2653
telemt_pool_swap_total 57
telemt_pool_force_close_total 1404
telemt_me_writer_close_signal_drop_total 129
telemt_me_draining_writers_reap_progress_total 19192
telemt_me_writer_removed_unexpected_total 580
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1784
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18015
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1316
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17788
telemt_me_writer_teardown_success_total{mode="normal"} 19799
telemt_me_writer_teardown_noop_total 19193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38992
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.733470
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38992
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 129
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 496
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 1932226
telemt_user_connections_current{user="hello"} 3950
telemt_user_octets_from_client{user="hello"} 34768808333 (32.38 GB)
telemt_user_octets_to_client{user="hello"} 850883721028 (792.45 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1367
telemt_user_unique_ips_recent_window{user="hello"} 539
```