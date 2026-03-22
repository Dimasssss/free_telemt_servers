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

# Server Metrics 2026-03-22 09:09:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 43374.5 (12h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1068539
telemt_connections_bad_total 59263
telemt_connections_current 1818
telemt_connections_me_current 1818
telemt_handshake_timeouts_total 48638
telemt_upstream_connect_attempt_total 17120
telemt_upstream_connect_success_total 17119
telemt_upstream_connect_attempts_per_request{bucket="1"} 17119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 39
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 490
telemt_me_reconnect_success_total 263
telemt_me_reader_eof_total 261
telemt_me_idle_close_by_peer_total 261
telemt_me_route_drop_no_conn_total 585055
telemt_me_route_drop_channel_closed_total 204
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 889424
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_shadow_rotate_total 350
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 6487
telemt_desync_full_logged_total 1850
telemt_desync_suppressed_total 4637
telemt_desync_frames_bucket_total{bucket="1_2"} 1931
telemt_desync_frames_bucket_total{bucket="3_10"} 2441
telemt_desync_frames_bucket_total{bucket="gt_10"} 2115
telemt_pool_swap_total 48
telemt_pool_force_close_total 1331
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 153
telemt_me_draining_writers_reap_progress_total 15520
telemt_me_writer_removed_unexpected_total 258
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1071
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14658
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14189
telemt_me_writer_teardown_success_total{mode="normal"} 15729
telemt_me_writer_teardown_noop_total 15522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31251
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31251
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.791482
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31251
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 153
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 241
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 887807
telemt_user_connections_current{user="hello"} 1818
telemt_user_octets_from_client{user="hello"} 12828024632 (11.95 GB)
telemt_user_octets_to_client{user="hello"} 285004164436 (265.43 GB)
telemt_user_unique_ips_current{user="hello"} 639
telemt_user_unique_ips_recent_window{user="hello"} 246
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 56740.6 (15h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1602494
telemt_connections_bad_total 154077
telemt_connections_current 1347
telemt_connections_me_current 1347
telemt_handshake_timeouts_total 44029
telemt_upstream_connect_attempt_total 34016
telemt_upstream_connect_success_total 33579
telemt_upstream_connect_fail_total 382
telemt_upstream_connect_attempts_per_request{bucket="1"} 33961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 382
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2508
telemt_me_reconnect_success_total 1078
telemt_me_reader_eof_total 979
telemt_me_idle_close_by_peer_total 979
telemt_me_route_drop_no_conn_total 796683
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1213427
telemt_me_endpoint_quarantine_total 493
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 448
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_me_writers_warm_current 7
telemt_desync_total 5435
telemt_desync_full_logged_total 3139
telemt_desync_suppressed_total 2296
telemt_desync_frames_bucket_total{bucket="1_2"} 1192
telemt_desync_frames_bucket_total{bucket="3_10"} 2114
telemt_desync_frames_bucket_total{bucket="gt_10"} 2129
telemt_pool_swap_total 58
telemt_pool_force_close_total 1581
telemt_me_writer_close_signal_drop_total 130
telemt_me_draining_writers_reap_progress_total 23040
telemt_me_writer_removed_unexpected_total 947
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2273
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21705
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21459
telemt_me_writer_teardown_success_total{mode="normal"} 23978
telemt_me_writer_teardown_noop_total 23040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47018
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.135630
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47018
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 130
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 868
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 1219601
telemt_user_connections_current{user="hello"} 1348
telemt_user_octets_from_client{user="hello"} 18342464998 (17.08 GB)
telemt_user_octets_to_client{user="hello"} 402401547204 (374.77 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 936
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 131600.6 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10095997
telemt_connections_bad_total 897496
telemt_connections_current 4700
telemt_connections_me_current 4700
telemt_handshake_timeouts_total 296608
telemt_upstream_connect_attempt_total 48479
telemt_upstream_connect_success_total 48399
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 48407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1971
telemt_me_reconnect_success_total 1026
telemt_me_reader_eof_total 1023
telemt_me_idle_close_by_peer_total 1022
telemt_me_route_drop_no_conn_total 6018521
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7937117
telemt_me_endpoint_quarantine_total 839
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 985
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 34291
telemt_desync_full_logged_total 11220
telemt_desync_suppressed_total 23071
telemt_desync_frames_bucket_total{bucket="1_2"} 7543
telemt_desync_frames_bucket_total{bucket="3_10"} 13354
telemt_desync_frames_bucket_total{bucket="gt_10"} 13394
telemt_pool_swap_total 142
telemt_pool_force_close_total 4715
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 723
telemt_me_draining_writers_reap_progress_total 44213
telemt_me_writer_removed_unexpected_total 983
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3733
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40920
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4397
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39498
telemt_me_writer_teardown_success_total{mode="normal"} 44653
telemt_me_writer_teardown_noop_total 44257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88910
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 191.376646
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88910
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 723
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 909
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 7927149
telemt_user_connections_current{user="hello"} 4700
telemt_user_octets_from_client{user="hello"} 128931589444 (120.08 GB)
telemt_user_octets_to_client{user="hello"} 2592286712156 (2.36 TB)
telemt_user_unique_ips_current{user="hello"} 1922
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 131602.2 (36h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8166531
telemt_connections_bad_total 733740
telemt_connections_current 3766
telemt_connections_me_current 3766
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 260243
telemt_upstream_connect_attempt_total 54450
telemt_upstream_connect_success_total 53967
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 54213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26334
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1128
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2935
telemt_me_reconnect_success_total 1111
telemt_me_reader_eof_total 1024
telemt_me_idle_close_by_peer_total 1024
telemt_me_route_drop_no_conn_total 2782564
telemt_me_route_drop_channel_closed_total 327
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6041666
telemt_me_endpoint_quarantine_total 837
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 1016
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 27791
telemt_desync_full_logged_total 9438
telemt_desync_suppressed_total 18353
telemt_desync_frames_bucket_total{bucket="1_2"} 6720
telemt_desync_frames_bucket_total{bucket="3_10"} 10758
telemt_desync_frames_bucket_total{bucket="gt_10"} 10313
telemt_pool_swap_total 144
telemt_pool_force_close_total 4309
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 467
telemt_me_draining_writers_reap_progress_total 42395
telemt_me_writer_removed_unexpected_total 1042
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3630
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39700
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4047
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 262
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38086
telemt_me_writer_teardown_success_total{mode="normal"} 43330
telemt_me_writer_teardown_noop_total 42401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85731
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 61.735895
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85731
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 467
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 936
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 5964014
telemt_user_connections_current{user="hello"} 3766
telemt_user_octets_from_client{user="hello"} 163400101575 (152.18 GB)
telemt_user_octets_to_client{user="hello"} 2847595698698 (2.59 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1405
telemt_user_unique_ips_recent_window{user="hello"} 614
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 131566.7 (36h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7828159
telemt_connections_bad_total 650844
telemt_connections_current 4832
telemt_connections_me_current 4832
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 259340
telemt_upstream_connect_attempt_total 59032
telemt_upstream_connect_success_total 58348
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 58495
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27461
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1329
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2917
telemt_me_reconnect_success_total 1294
telemt_me_reader_eof_total 1188
telemt_me_idle_close_by_peer_total 1188
telemt_me_route_drop_no_conn_total 3162940
telemt_me_route_drop_channel_closed_total 199
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5839501
telemt_me_endpoint_quarantine_total 915
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 966
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_me_writers_active_current 107
telemt_me_writers_warm_current 21
telemt_desync_total 27393
telemt_desync_full_logged_total 9329
telemt_desync_suppressed_total 18064
telemt_desync_frames_bucket_total{bucket="1_2"} 6618
telemt_desync_frames_bucket_total{bucket="3_10"} 10515
telemt_desync_frames_bucket_total{bucket="gt_10"} 10260
telemt_pool_swap_total 139
telemt_pool_force_close_total 4147
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 485
telemt_me_draining_writers_reap_progress_total 43398
telemt_me_writer_removed_unexpected_total 1206
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3912
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40676
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3834
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 313
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39251
telemt_me_writer_teardown_success_total{mode="normal"} 44588
telemt_me_writer_teardown_noop_total 43410
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87998
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.017426
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87998
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 485
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1131
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 5832360
telemt_user_connections_current{user="hello"} 4832
telemt_user_octets_from_client{user="hello"} 149996347803 (139.69 GB)
telemt_user_octets_to_client{user="hello"} 2586159396915 (2.35 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 2020
telemt_user_unique_ips_recent_window{user="hello"} 558
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 1846.5 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 727530
telemt_connections_bad_total 63610
telemt_connections_current 6203
telemt_connections_me_current 6203
telemt_handshake_timeouts_total 8449
telemt_upstream_connect_attempt_total 726
telemt_upstream_connect_success_total 684
telemt_upstream_connect_fail_total 18
telemt_upstream_connect_attempts_per_request{bucket="1"} 702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 302
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 360
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 18
telemt_me_keepalive_timeout_total 129
telemt_me_reconnect_attempts_total 97
telemt_me_reconnect_success_total 51
telemt_me_reader_eof_total 49
telemt_me_idle_close_by_peer_total 49
telemt_me_route_drop_no_conn_total 1577197
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 597517
telemt_me_endpoint_quarantine_total 3
telemt_me_single_endpoint_shadow_rotate_total 15
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_me_writers_active_current 90
telemt_me_writers_warm_current 15
telemt_desync_total 1107
telemt_desync_full_logged_total 277
telemt_desync_suppressed_total 830
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 444
telemt_desync_frames_bucket_total{bucket="gt_10"} 442
telemt_pool_force_close_total 2
telemt_me_writer_close_signal_drop_total 6
telemt_me_draining_writers_reap_progress_total 445
telemt_me_writer_removed_unexpected_total 50
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 429
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 443
telemt_me_writer_teardown_success_total{mode="normal"} 495
telemt_me_writer_teardown_noop_total 445
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 940
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.326215
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 940
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 6
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 597472
telemt_user_connections_current{user="hello"} 6203
telemt_user_octets_from_client{user="hello"} 4432751644 (4.13 GB)
telemt_user_octets_to_client{user="hello"} 19122601276 (17.81 GB)
telemt_user_unique_ips_current{user="hello"} 2191
telemt_user_unique_ips_recent_window{user="hello"} 1235
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 131572.8 (36h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7462730
telemt_connections_bad_total 670360
telemt_connections_current 4275
telemt_connections_me_current 4275
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 153125
telemt_upstream_connect_attempt_total 75162
telemt_upstream_connect_success_total 74341
telemt_upstream_connect_fail_total 702
telemt_upstream_connect_attempts_per_request{bucket="1"} 75043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28500
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 442
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 702
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70407
telemt_me_reconnect_success_total 2048
telemt_me_reader_eof_total 1793
telemt_me_idle_close_by_peer_total 1792
telemt_me_route_drop_no_conn_total 2947146
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5864436
telemt_me_endpoint_quarantine_total 885
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 993
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_me_writers_active_current 68
telemt_me_writers_warm_current 23
telemt_desync_total 29569
telemt_desync_full_logged_total 10275
telemt_desync_suppressed_total 19294
telemt_desync_frames_bucket_total{bucket="1_2"} 5896
telemt_desync_frames_bucket_total{bucket="3_10"} 11384
telemt_desync_frames_bucket_total{bucket="gt_10"} 12289
telemt_pool_swap_total 137
telemt_pool_force_close_total 3932
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 466
telemt_me_draining_writers_reap_progress_total 45533
telemt_me_writer_removed_unexpected_total 1823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4624
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42758
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3490
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 442
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41601
telemt_me_writer_teardown_success_total{mode="normal"} 47382
telemt_me_writer_teardown_noop_total 45534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 92913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 92916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 92916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 92916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 92916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 92916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 92916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 92916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 92916
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.375290
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 92916
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 466
telemt_me_refill_failed_total 4229
telemt_me_writer_restored_same_endpoint_total 1696
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5862544
telemt_user_connections_current{user="hello"} 4275
telemt_user_octets_from_client{user="hello"} 147897105515 (137.74 GB)
telemt_user_octets_to_client{user="hello"} 2413461118735 (2.20 TB)
telemt_user_msgs_from_client{user="hello"} 115484
telemt_user_msgs_to_client{user="hello"} 517108
telemt_user_unique_ips_current{user="hello"} 1645
telemt_user_unique_ips_recent_window{user="hello"} 598
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 68408.8 (19h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5993395
telemt_connections_bad_total 233704
telemt_connections_current 4951
telemt_connections_me_current 4951
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2384275
telemt_upstream_connect_attempt_total 36620
telemt_upstream_connect_success_total 36365
telemt_upstream_connect_fail_total 248
telemt_upstream_connect_attempts_per_request{bucket="1"} 36613
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14802
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 248
telemt_me_reconnect_attempts_total 47424
telemt_me_reconnect_success_total 1231
telemt_me_reader_eof_total 900
telemt_me_idle_close_by_peer_total 900
telemt_me_route_drop_no_conn_total 1537457
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3009139
telemt_me_endpoint_quarantine_total 463
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 520
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 91
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 16508
telemt_desync_full_logged_total 5588
telemt_desync_suppressed_total 10920
telemt_desync_frames_bucket_total{bucket="1_2"} 3242
telemt_desync_frames_bucket_total{bucket="3_10"} 6363
telemt_desync_frames_bucket_total{bucket="gt_10"} 6903
telemt_pool_swap_total 72
telemt_pool_force_close_total 2160
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 203
telemt_me_draining_writers_reap_progress_total 24624
telemt_me_writer_removed_unexpected_total 971
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2138
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23479
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 278
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22464
telemt_me_writer_teardown_success_total{mode="normal"} 25617
telemt_me_writer_teardown_noop_total 24630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50247
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.618995
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50247
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 203
telemt_me_refill_failed_total 2687
telemt_me_writer_restored_same_endpoint_total 1103
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3010140
telemt_user_connections_current{user="hello"} 4951
telemt_user_octets_from_client{user="hello"} 75941117068 (70.73 GB)
telemt_user_octets_to_client{user="hello"} 1304309851786 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 2014
telemt_user_unique_ips_recent_window{user="hello"} 620
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 49379.3 (13h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451563
telemt_connections_bad_total 3246
telemt_connections_current 937
telemt_connections_me_current 937
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8706
telemt_upstream_connect_attempt_total 26150
telemt_upstream_connect_success_total 26090
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 26145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13580
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 258
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 1024
telemt_me_reconnect_success_total 397
telemt_me_reader_eof_total 393
telemt_me_idle_close_by_peer_total 393
telemt_me_route_drop_no_conn_total 145826
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407839
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 423
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
telemt_desync_total 1889
telemt_desync_full_logged_total 552
telemt_desync_suppressed_total 1337
telemt_desync_frames_bucket_total{bucket="1_2"} 539
telemt_desync_frames_bucket_total{bucket="3_10"} 737
telemt_desync_frames_bucket_total{bucket="gt_10"} 613
telemt_pool_swap_total 53
telemt_pool_force_close_total 1222
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 21069
telemt_me_writer_removed_unexpected_total 376
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1489
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19973
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1194
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 28
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19847
telemt_me_writer_teardown_success_total{mode="normal"} 21462
telemt_me_writer_teardown_noop_total 21069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42531
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.969507
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42531
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 346
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 409969
telemt_user_connections_current{user="hello"} 937
telemt_user_octets_from_client{user="hello"} 8184508817 (7.62 GB)
telemt_user_octets_to_client{user="hello"} 205978277055 (191.83 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 131577.6 (36h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9195568
telemt_connections_bad_total 1064207
telemt_connections_current 6350
telemt_connections_me_current 6350
telemt_handshake_timeouts_total 252503
telemt_upstream_connect_attempt_total 51039
telemt_upstream_connect_success_total 50844
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 50995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25641
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_reconnect_attempts_total 1910
telemt_me_reconnect_success_total 1041
telemt_me_reader_eof_total 1012
telemt_me_idle_close_by_peer_total 1012
telemt_me_route_drop_no_conn_total 2595235
telemt_me_route_drop_channel_closed_total 65
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6814713
telemt_me_endpoint_quarantine_total 937
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1001
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 27466
telemt_desync_full_logged_total 8995
telemt_desync_suppressed_total 18471
telemt_desync_frames_bucket_total{bucket="1_2"} 6803
telemt_desync_frames_bucket_total{bucket="3_10"} 10007
telemt_desync_frames_bucket_total{bucket="gt_10"} 10656
telemt_pool_swap_total 146
telemt_pool_force_close_total 3902
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 475
telemt_me_draining_writers_reap_progress_total 46025
telemt_me_writer_removed_unexpected_total 973
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3687
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43341
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 102
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42123
telemt_me_writer_teardown_success_total{mode="normal"} 47028
telemt_me_writer_teardown_noop_total 46027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 92955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93055
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.631296
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93055
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 475
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 913
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6787621
telemt_user_connections_current{user="hello"} 6350
telemt_user_octets_from_client{user="hello"} 132022213900 (122.96 GB)
telemt_user_octets_to_client{user="hello"} 3184750393276 (2.90 TB)
telemt_user_unique_ips_current{user="hello"} 2295
telemt_user_unique_ips_recent_window{user="hello"} 827
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 131573.8 (36h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7996559
telemt_connections_bad_total 888426
telemt_connections_current 3106
telemt_connections_me_current 3106
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 210895
telemt_upstream_connect_attempt_total 75469
telemt_upstream_connect_success_total 74936
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 75400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30102
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1965
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_reconnect_attempts_total 6474
telemt_me_reconnect_success_total 1487
telemt_me_reader_eof_total 1331
telemt_me_idle_close_by_peer_total 1331
telemt_me_seq_mismatch_total 62
telemt_me_route_drop_no_conn_total 2768468
telemt_me_route_drop_channel_closed_total 237
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6085919
telemt_me_endpoint_quarantine_total 1033
telemt_me_single_endpoint_outage_enter_total 34
telemt_me_single_endpoint_outage_exit_total 34
telemt_me_single_endpoint_outage_reconnect_attempt_total 34
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 34
telemt_me_single_endpoint_shadow_rotate_total 999
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_me_writers_active_current 41
telemt_desync_total 26360
telemt_desync_full_logged_total 8762
telemt_desync_suppressed_total 17598
telemt_desync_frames_bucket_total{bucket="1_2"} 6490
telemt_desync_frames_bucket_total{bucket="3_10"} 9674
telemt_desync_frames_bucket_total{bucket="gt_10"} 10196
telemt_pool_swap_total 143
telemt_pool_force_close_total 3852
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 475
telemt_me_draining_writers_reap_progress_total 44673
telemt_me_writer_removed_unexpected_total 1347
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4327
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41755
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40821
telemt_me_writer_teardown_success_total{mode="normal"} 46082
telemt_me_writer_teardown_noop_total 44677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 90473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90759
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.284072
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90759
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 475
telemt_me_refill_failed_total 287
telemt_me_writer_restored_same_endpoint_total 1161
telemt_me_writer_restored_fallback_total 86
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 6094699
telemt_user_connections_current{user="hello"} 3106
telemt_user_octets_from_client{user="hello"} 111688914385 (104.02 GB)
telemt_user_octets_to_client{user="hello"} 2611769044443 (2.38 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1039
telemt_user_unique_ips_recent_window{user="hello"} 1359
```