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

# Server Metrics 2026-03-22 10:31:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 48282.7 (13h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1286864
telemt_connections_bad_total 67638
telemt_connections_current 1832
telemt_connections_me_current 1832
telemt_handshake_timeouts_total 59523
telemt_upstream_connect_attempt_total 18693
telemt_upstream_connect_success_total 18692
telemt_upstream_connect_attempts_per_request{bucket="1"} 18692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6457
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12176
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 48
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 561
telemt_me_reconnect_success_total 291
telemt_me_reader_eof_total 290
telemt_me_idle_close_by_peer_total 290
telemt_me_route_drop_no_conn_total 701977
telemt_me_route_drop_channel_closed_total 327
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1074671
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_endpoint_quarantine_total 338
telemt_me_single_endpoint_shadow_rotate_total 388
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
telemt_me_writers_active_current 43
telemt_desync_total 7133
telemt_desync_full_logged_total 2087
telemt_desync_suppressed_total 5046
telemt_desync_frames_bucket_total{bucket="1_2"} 2080
telemt_desync_frames_bucket_total{bucket="3_10"} 2694
telemt_desync_frames_bucket_total{bucket="gt_10"} 2359
telemt_pool_swap_total 53
telemt_pool_force_close_total 1545
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 204
telemt_me_draining_writers_reap_progress_total 17014
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1180
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16039
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1512
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 33
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15469
telemt_me_writer_teardown_success_total{mode="normal"} 17219
telemt_me_writer_teardown_noop_total 17016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34235
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 87.804993
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34235
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 204
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 266
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1072769
telemt_user_connections_current{user="hello"} 1832
telemt_user_octets_from_client{user="hello"} 17167463936 (15.99 GB)
telemt_user_octets_to_client{user="hello"} 339707808280 (316.38 GB)
telemt_user_unique_ips_current{user="hello"} 675
telemt_user_unique_ips_recent_window{user="hello"} 273
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 61649.1 (17h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2071310
telemt_connections_bad_total 174016
telemt_connections_current 1579
telemt_connections_me_current 1579
telemt_handshake_timeouts_total 49849
telemt_upstream_connect_attempt_total 36385
telemt_upstream_connect_success_total 35894
telemt_upstream_connect_fail_total 431
telemt_upstream_connect_attempts_per_request{bucket="1"} 36325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15705
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 431
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3155
telemt_me_reconnect_success_total 1409
telemt_me_reader_eof_total 1297
telemt_me_idle_close_by_peer_total 1297
telemt_me_route_drop_no_conn_total 1530772
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1621151
telemt_me_endpoint_quarantine_total 529
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 489
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 6714
telemt_desync_full_logged_total 3799
telemt_desync_suppressed_total 2915
telemt_desync_frames_bucket_total{bucket="1_2"} 1530
telemt_desync_frames_bucket_total{bucket="3_10"} 2624
telemt_desync_frames_bucket_total{bucket="gt_10"} 2560
telemt_pool_swap_total 62
telemt_pool_force_close_total 1754
telemt_me_writer_close_signal_drop_total 144
telemt_me_draining_writers_reap_progress_total 24901
telemt_me_writer_removed_unexpected_total 1263
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2712
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23446
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1570
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23147
telemt_me_writer_teardown_success_total{mode="normal"} 26158
telemt_me_writer_teardown_noop_total 24901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51059
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.501111
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51059
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 144
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 1172
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 21
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 1627126
telemt_user_connections_current{user="hello"} 1579
telemt_user_octets_from_client{user="hello"} 22330291514 (20.80 GB)
telemt_user_octets_to_client{user="hello"} 452848104248 (421.75 GB)
telemt_user_msgs_from_client{user="hello"} 21111
telemt_user_msgs_to_client{user="hello"} 48002
telemt_user_unique_ips_current{user="hello"} 975
telemt_user_unique_ips_recent_window{user="hello"} 697
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 136509.1 (37h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11301175
telemt_connections_bad_total 963515
telemt_connections_current 5119
telemt_connections_me_current 5119
telemt_handshake_timeouts_total 310831
telemt_upstream_connect_attempt_total 49890
telemt_upstream_connect_success_total 49810
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 49818
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27083
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2137
telemt_me_reconnect_success_total 1098
telemt_me_reader_eof_total 1081
telemt_me_idle_close_by_peer_total 1080
telemt_me_route_drop_no_conn_total 8118228
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8986605
telemt_me_endpoint_quarantine_total 874
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1017
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
telemt_desync_total 37586
telemt_desync_full_logged_total 12164
telemt_desync_suppressed_total 25422
telemt_desync_frames_bucket_total{bucket="1_2"} 8459
telemt_desync_frames_bucket_total{bucket="3_10"} 14595
telemt_desync_frames_bucket_total{bucket="gt_10"} 14532
telemt_pool_swap_total 147
telemt_pool_force_close_total 4942
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 767
telemt_me_draining_writers_reap_progress_total 45503
telemt_me_writer_removed_unexpected_total 1039
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3887
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42079
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4609
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 333
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40561
telemt_me_writer_teardown_success_total{mode="normal"} 45966
telemt_me_writer_teardown_noop_total 45547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91513
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 208.663428
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91513
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 767
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 8975923
telemt_user_connections_current{user="hello"} 5119
telemt_user_octets_from_client{user="hello"} 139828131336 (130.23 GB)
telemt_user_octets_to_client{user="hello"} 2698587110612 (2.45 TB)
telemt_user_unique_ips_current{user="hello"} 1969
telemt_user_unique_ips_recent_window{user="hello"} 972
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 136510.4 (37h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8843532
telemt_connections_bad_total 791054
telemt_connections_current 4012
telemt_connections_me_current 4012
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 271613
telemt_upstream_connect_attempt_total 56229
telemt_upstream_connect_success_total 55661
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 55921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27097
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27279
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3083
telemt_me_reconnect_success_total 1235
telemt_me_reader_eof_total 1124
telemt_me_idle_close_by_peer_total 1124
telemt_me_route_drop_no_conn_total 3582895
telemt_me_route_drop_channel_closed_total 365
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6581169
telemt_me_endpoint_quarantine_total 860
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 1048
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
telemt_me_writers_active_current 85
telemt_desync_total 29682
telemt_desync_full_logged_total 10067
telemt_desync_suppressed_total 19615
telemt_desync_frames_bucket_total{bucket="1_2"} 7182
telemt_desync_frames_bucket_total{bucket="3_10"} 11452
telemt_desync_frames_bucket_total{bucket="gt_10"} 11048
telemt_pool_swap_total 147
telemt_pool_force_close_total 4461
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 497
telemt_me_draining_writers_reap_progress_total 43838
telemt_me_writer_removed_unexpected_total 1159
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3826
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41065
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4156
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 305
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39377
telemt_me_writer_teardown_success_total{mode="normal"} 44891
telemt_me_writer_teardown_noop_total 43844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88735
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 64.397782
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88735
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 497
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 1054
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 6503084
telemt_user_connections_current{user="hello"} 4012
telemt_user_octets_from_client{user="hello"} 171446983559 (159.67 GB)
telemt_user_octets_to_client{user="hello"} 3003573710834 (2.73 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1610
telemt_user_unique_ips_recent_window{user="hello"} 615
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 136475.0 (37h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8392060
telemt_connections_bad_total 701737
telemt_connections_current 4270
telemt_connections_me_current 4270
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 271217
telemt_upstream_connect_attempt_total 60646
telemt_upstream_connect_success_total 59946
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 60093
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 990
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 238
telemt_me_reconnect_attempts_total 3526
telemt_me_reconnect_success_total 1478
telemt_me_reader_eof_total 1361
telemt_me_idle_close_by_peer_total 1361
telemt_me_route_drop_no_conn_total 3533227
telemt_me_route_drop_channel_closed_total 233
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6288717
telemt_me_endpoint_quarantine_total 941
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 1000
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 29154
telemt_desync_full_logged_total 9916
telemt_desync_suppressed_total 19238
telemt_desync_frames_bucket_total{bucket="1_2"} 7032
telemt_desync_frames_bucket_total{bucket="3_10"} 11231
telemt_desync_frames_bucket_total{bucket="gt_10"} 10891
telemt_pool_swap_total 144
telemt_pool_force_close_total 4394
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 522
telemt_me_draining_writers_reap_progress_total 44793
telemt_me_writer_removed_unexpected_total 1387
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4202
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41925
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4000
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 394
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40399
telemt_me_writer_teardown_success_total{mode="normal"} 46127
telemt_me_writer_teardown_noop_total 44810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90937
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.321505
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90937
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 522
telemt_me_refill_failed_total 105
telemt_me_writer_restored_same_endpoint_total 1299
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 50
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 6280494
telemt_user_connections_current{user="hello"} 4270
telemt_user_octets_from_client{user="hello"} 156439405983 (145.70 GB)
telemt_user_octets_to_client{user="hello"} 2737877915919 (2.49 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1868
telemt_user_unique_ips_recent_window{user="hello"} 624
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 6754.4 (1h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2885305
telemt_connections_bad_total 198917
telemt_connections_current 6877
telemt_connections_me_current 6877
telemt_handshake_timeouts_total 40823
telemt_upstream_connect_attempt_total 9069
telemt_upstream_connect_success_total 8595
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 8940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1826
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2707
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_keepalive_timeout_total 310
telemt_me_reconnect_attempts_total 488
telemt_me_reconnect_success_total 192
telemt_me_reader_eof_total 135
telemt_me_idle_close_by_peer_total 135
telemt_me_route_drop_no_conn_total 6609764
telemt_me_route_drop_channel_closed_total 14
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2408729
telemt_me_endpoint_quarantine_total 40
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 55
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
telemt_desync_total 3710
telemt_desync_full_logged_total 940
telemt_desync_suppressed_total 2770
telemt_desync_frames_bucket_total{bucket="1_2"} 659
telemt_desync_frames_bucket_total{bucket="3_10"} 1450
telemt_desync_frames_bucket_total{bucket="gt_10"} 1601
telemt_pool_swap_total 5
telemt_pool_force_close_total 233
telemt_me_writer_close_signal_drop_total 87
telemt_me_draining_writers_reap_progress_total 1832
telemt_me_writer_removed_unexpected_total 179
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 314
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1682
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 100
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1599
telemt_me_writer_teardown_success_total{mode="normal"} 1996
telemt_me_writer_teardown_noop_total 1833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3829
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.811917
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3829
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 87
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 135
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2413593
telemt_user_connections_current{user="hello"} 6878
telemt_user_octets_from_client{user="hello"} 12769003454 (11.89 GB)
telemt_user_octets_to_client{user="hello"} 70482839535 (65.64 GB)
telemt_user_msgs_from_client{user="hello"} 6014
telemt_user_msgs_to_client{user="hello"} 4995
telemt_user_unique_ips_current{user="hello"} 2486
telemt_user_unique_ips_recent_window{user="hello"} 1465
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 136481.2 (37h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8072475
telemt_connections_bad_total 700400
telemt_connections_current 5198
telemt_connections_me_current 5198
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 164152
telemt_upstream_connect_attempt_total 85901
telemt_upstream_connect_success_total 85048
telemt_upstream_connect_fail_total 733
telemt_upstream_connect_attempts_per_request{bucket="1"} 85781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 53382
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30217
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1241
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 733
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 70628
telemt_me_reconnect_success_total 2171
telemt_me_reader_eof_total 1907
telemt_me_idle_close_by_peer_total 1906
telemt_me_route_drop_no_conn_total 3532923
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 45
telemt_me_route_drop_queue_full_profile_total{profile="high"} 45
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6375508
telemt_me_endpoint_quarantine_total 918
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1027
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
telemt_me_writers_active_current 45
telemt_desync_total 32208
telemt_desync_full_logged_total 11112
telemt_desync_suppressed_total 21096
telemt_desync_frames_bucket_total{bucket="1_2"} 6550
telemt_desync_frames_bucket_total{bucket="3_10"} 12393
telemt_desync_frames_bucket_total{bucket="gt_10"} 13265
telemt_pool_swap_total 141
telemt_pool_force_close_total 4096
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 496
telemt_me_draining_writers_reap_progress_total 47126
telemt_me_writer_removed_unexpected_total 1936
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4865
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44222
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3569
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 527
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43030
telemt_me_writer_teardown_success_total{mode="normal"} 49087
telemt_me_writer_teardown_noop_total 47127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96214
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.440979
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96214
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 496
telemt_me_refill_failed_total 4233
telemt_me_writer_restored_same_endpoint_total 1803
telemt_me_writer_restored_fallback_total 41
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7333
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 6379200
telemt_user_connections_current{user="hello"} 5198
telemt_user_octets_from_client{user="hello"} 154831404467 (144.20 GB)
telemt_user_octets_to_client{user="hello"} 2540487517133 (2.31 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1954
telemt_user_unique_ips_recent_window{user="hello"} 789
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 73317.3 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7035556
telemt_connections_bad_total 264390
telemt_connections_current 4271
telemt_connections_me_current 4271
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2870479
telemt_upstream_connect_attempt_total 38450
telemt_upstream_connect_success_total 38171
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 38443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22316
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15752
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_reconnect_attempts_total 47664
telemt_me_reconnect_success_total 1323
telemt_me_reader_eof_total 988
telemt_me_idle_close_by_peer_total 988
telemt_me_route_drop_no_conn_total 2121009
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3491159
telemt_me_endpoint_quarantine_total 504
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 559
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 18758
telemt_desync_full_logged_total 6294
telemt_desync_suppressed_total 12464
telemt_desync_frames_bucket_total{bucket="1_2"} 3827
telemt_desync_frames_bucket_total{bucket="3_10"} 7194
telemt_desync_frames_bucket_total{bucket="gt_10"} 7737
telemt_pool_swap_total 77
telemt_pool_force_close_total 2365
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 233
telemt_me_draining_writers_reap_progress_total 26239
telemt_me_writer_removed_unexpected_total 1057
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2344
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24976
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 354
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23874
telemt_me_writer_teardown_success_total{mode="normal"} 27320
telemt_me_writer_teardown_noop_total 26245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53565
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.989752
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53565
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 233
telemt_me_refill_failed_total 2694
telemt_me_writer_restored_same_endpoint_total 1181
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 3490321
telemt_user_connections_current{user="hello"} 4271
telemt_user_octets_from_client{user="hello"} 83567995472 (77.83 GB)
telemt_user_octets_to_client{user="hello"} 1431752820402 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1670
telemt_user_unique_ips_recent_window{user="hello"} 669
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 54288.0 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 548952
telemt_connections_bad_total 3820
telemt_connections_current 940
telemt_connections_me_current 940
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 10235
telemt_upstream_connect_attempt_total 28444
telemt_upstream_connect_success_total 28379
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 28437
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14853
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_reconnect_attempts_total 1203
telemt_me_reconnect_success_total 510
telemt_me_reader_eof_total 507
telemt_me_idle_close_by_peer_total 507
telemt_me_route_drop_no_conn_total 180000
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 496832
telemt_me_endpoint_quarantine_total 489
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 460
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
telemt_me_writers_active_current 91
telemt_desync_total 2516
telemt_desync_full_logged_total 721
telemt_desync_suppressed_total 1795
telemt_desync_frames_bucket_total{bucket="1_2"} 733
telemt_desync_frames_bucket_total{bucket="3_10"} 976
telemt_desync_frames_bucket_total{bucket="gt_10"} 807
telemt_pool_swap_total 57
telemt_pool_force_close_total 1354
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 23003
telemt_me_writer_removed_unexpected_total 491
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1722
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21789
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1303
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 51
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21649
telemt_me_writer_teardown_success_total{mode="normal"} 23511
telemt_me_writer_teardown_noop_total 23003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46514
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.441250
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46514
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 456
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 498796
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 9770355073 (9.10 GB)
telemt_user_octets_to_client{user="hello"} 239353420691 (222.92 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 136485.5 (37h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9820847
telemt_connections_bad_total 1147648
telemt_connections_current 5789
telemt_connections_me_current 5789
telemt_handshake_timeouts_total 263809
telemt_upstream_connect_attempt_total 52436
telemt_upstream_connect_success_total 52236
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 52390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26370
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2033
telemt_me_reconnect_success_total 1081
telemt_me_reader_eof_total 1048
telemt_me_idle_close_by_peer_total 1048
telemt_me_route_drop_no_conn_total 2815447
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 28
telemt_me_route_drop_queue_full_profile_total{profile="high"} 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7312390
telemt_me_endpoint_quarantine_total 963
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1031
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
telemt_me_writers_active_current 43
telemt_desync_total 29685
telemt_desync_full_logged_total 9727
telemt_desync_suppressed_total 19958
telemt_desync_frames_bucket_total{bucket="1_2"} 7306
telemt_desync_frames_bucket_total{bucket="3_10"} 10867
telemt_desync_frames_bucket_total{bucket="gt_10"} 11512
telemt_pool_swap_total 151
telemt_pool_force_close_total 4088
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 492
telemt_me_draining_writers_reap_progress_total 47287
telemt_me_writer_removed_unexpected_total 1007
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3813
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44513
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43199
telemt_me_writer_teardown_success_total{mode="normal"} 48326
telemt_me_writer_teardown_noop_total 47289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95615
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.055267
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95615
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 492
telemt_me_refill_failed_total 49
telemt_me_writer_restored_same_endpoint_total 946
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 7284435
telemt_user_connections_current{user="hello"} 5789
telemt_user_octets_from_client{user="hello"} 140998564096 (131.32 GB)
telemt_user_octets_to_client{user="hello"} 3392342995856 (3.09 TB)
telemt_user_unique_ips_current{user="hello"} 2209
telemt_user_unique_ips_recent_window{user="hello"} 763
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 136482.2 (37h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8538060
telemt_connections_bad_total 959473
telemt_connections_current 4718
telemt_connections_me_current 4718
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 221017
telemt_upstream_connect_attempt_total 76948
telemt_upstream_connect_success_total 76401
telemt_upstream_connect_fail_total 478
telemt_upstream_connect_attempts_per_request{bucket="1"} 76879
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42668
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30856
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1968
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 478
telemt_me_reconnect_attempts_total 6590
telemt_me_reconnect_success_total 1549
telemt_me_reader_eof_total 1374
telemt_me_idle_close_by_peer_total 1374
telemt_me_seq_mismatch_total 65
telemt_me_route_drop_no_conn_total 3053190
telemt_me_route_drop_channel_closed_total 267
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6523191
telemt_me_endpoint_quarantine_total 1062
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1033
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 28834
telemt_desync_full_logged_total 9510
telemt_desync_suppressed_total 19324
telemt_desync_frames_bucket_total{bucket="1_2"} 7110
telemt_desync_frames_bucket_total{bucket="3_10"} 10639
telemt_desync_frames_bucket_total{bucket="gt_10"} 11085
telemt_pool_swap_total 148
telemt_pool_force_close_total 4018
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 495
telemt_me_draining_writers_reap_progress_total 45972
telemt_me_writer_removed_unexpected_total 1392
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4466
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42961
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3720
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 298
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41954
telemt_me_writer_teardown_success_total{mode="normal"} 47427
telemt_me_writer_teardown_noop_total 45976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93403
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.622565
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93403
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 495
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 1206
telemt_me_writer_restored_fallback_total 89
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 6531286
telemt_user_connections_current{user="hello"} 4718
telemt_user_octets_from_client{user="hello"} 118319573089 (110.19 GB)
telemt_user_octets_to_client{user="hello"} 2751221875543 (2.50 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1794
telemt_user_unique_ips_recent_window{user="hello"} 653
```