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

# Server Metrics 2026-03-22 03:32:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 23147.8 (6h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 349637
telemt_connections_bad_total 23127
telemt_connections_current 1070
telemt_connections_me_current 1070
telemt_handshake_timeouts_total 19798
telemt_upstream_connect_attempt_total 9698
telemt_upstream_connect_success_total 9697
telemt_upstream_connect_attempts_per_request{bucket="1"} 9697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6224
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 274
telemt_me_reconnect_success_total 148
telemt_me_reader_eof_total 144
telemt_me_idle_close_by_peer_total 144
telemt_me_route_drop_no_conn_total 65607
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 288477
telemt_me_endpoint_quarantine_total 186
telemt_me_single_endpoint_shadow_rotate_total 195
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
telemt_desync_total 2613
telemt_desync_full_logged_total 714
telemt_desync_suppressed_total 1899
telemt_desync_frames_bucket_total{bucket="1_2"} 895
telemt_desync_frames_bucket_total{bucket="3_10"} 983
telemt_desync_frames_bucket_total{bucket="gt_10"} 735
telemt_pool_swap_total 25
telemt_pool_force_close_total 654
telemt_me_writer_close_signal_drop_total 46
telemt_me_draining_writers_reap_progress_total 8760
telemt_me_writer_removed_unexpected_total 143
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 586
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8308
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 649
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8106
telemt_me_writer_teardown_success_total{mode="normal"} 8894
telemt_me_writer_teardown_noop_total 8761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17561
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 17621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 17653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 17655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 17655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 17655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 17655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 17655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 17655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 17655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 17655
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.016624
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 17655
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 46
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 134
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 287943
telemt_user_connections_current{user="hello"} 1070
telemt_user_octets_from_client{user="hello"} 3831651916 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 101214519852 (94.26 GB)
telemt_user_unique_ips_current{user="hello"} 417
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 36514.0 (10h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 827843
telemt_connections_bad_total 53351
telemt_connections_current 511
telemt_connections_me_current 511
telemt_handshake_timeouts_total 30304
telemt_upstream_connect_attempt_total 17091
telemt_upstream_connect_success_total 16828
telemt_upstream_connect_fail_total 240
telemt_upstream_connect_attempts_per_request{bucket="1"} 17068
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9399
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 240
telemt_me_reconnect_attempts_total 1391
telemt_me_reconnect_success_total 525
telemt_me_reader_eof_total 465
telemt_me_idle_close_by_peer_total 465
telemt_me_route_drop_no_conn_total 347103
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 654763
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 296
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 2803
telemt_desync_full_logged_total 1608
telemt_desync_suppressed_total 1195
telemt_desync_frames_bucket_total{bucket="1_2"} 593
telemt_desync_frames_bucket_total{bucket="3_10"} 1066
telemt_desync_frames_bucket_total{bucket="gt_10"} 1144
telemt_pool_swap_total 39
telemt_pool_force_close_total 1049
telemt_me_writer_close_signal_drop_total 73
telemt_me_draining_writers_reap_progress_total 15161
telemt_me_writer_removed_unexpected_total 442
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1260
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14353
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1027
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14112
telemt_me_writer_teardown_success_total{mode="normal"} 15613
telemt_me_writer_teardown_noop_total 15161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30774
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.787555
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30774
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 73
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 392
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 653814
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 10617807592 (9.89 GB)
telemt_user_octets_to_client{user="hello"} 232717126732 (216.73 GB)
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 111374.0 (30h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7850409
telemt_connections_bad_total 647971
telemt_connections_current 1789
telemt_connections_me_current 1789
telemt_handshake_timeouts_total 258134
telemt_upstream_connect_attempt_total 41490
telemt_upstream_connect_success_total 41413
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 41420
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18724
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1600
telemt_me_reconnect_success_total 837
telemt_me_reader_eof_total 846
telemt_me_idle_close_by_peer_total 846
telemt_me_route_drop_no_conn_total 4552034
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6343996
telemt_me_endpoint_quarantine_total 717
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 834
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26679
telemt_desync_full_logged_total 8847
telemt_desync_suppressed_total 17832
telemt_desync_frames_bucket_total{bucket="1_2"} 5761
telemt_desync_frames_bucket_total{bucket="3_10"} 10421
telemt_desync_frames_bucket_total{bucket="gt_10"} 10497
telemt_pool_swap_total 120
telemt_pool_force_close_total 3962
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 608
telemt_me_draining_writers_reap_progress_total 37847
telemt_me_writer_removed_unexpected_total 814
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3159
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35037
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3722
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33885
telemt_me_writer_teardown_success_total{mode="normal"} 38196
telemt_me_writer_teardown_noop_total 37891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76087
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 161.800551
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76087
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 608
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 746
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6336026
telemt_user_connections_current{user="hello"} 1789
telemt_user_octets_from_client{user="hello"} 107657516188 (100.26 GB)
telemt_user_octets_to_client{user="hello"} 2120332651536 (1.93 TB)
telemt_user_unique_ips_current{user="hello"} 913
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 111375.4 (30h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6495032
telemt_connections_bad_total 590781
telemt_connections_current 1704
telemt_connections_me_current 1704
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 214976
telemt_upstream_connect_attempt_total 45462
telemt_upstream_connect_success_total 45070
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 45265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22339
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22141
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1959
telemt_me_reconnect_success_total 890
telemt_me_reader_eof_total 862
telemt_me_idle_close_by_peer_total 862
telemt_me_route_drop_no_conn_total 2271640
telemt_me_route_drop_channel_closed_total 272
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4841576
telemt_me_endpoint_quarantine_total 698
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 859
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
telemt_desync_total 22816
telemt_desync_full_logged_total 7777
telemt_desync_suppressed_total 15039
telemt_desync_frames_bucket_total{bucket="1_2"} 5480
telemt_desync_frames_bucket_total{bucket="3_10"} 8872
telemt_desync_frames_bucket_total{bucket="gt_10"} 8464
telemt_pool_swap_total 121
telemt_pool_force_close_total 3594
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 368
telemt_me_draining_writers_reap_progress_total 36337
telemt_me_writer_removed_unexpected_total 846
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3015
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34106
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3381
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32743
telemt_me_writer_teardown_success_total{mode="normal"} 37121
telemt_me_writer_teardown_noop_total 36343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73444
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73464
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.462225
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73464
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 368
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 779
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4763654
telemt_user_connections_current{user="hello"} 1704
telemt_user_octets_from_client{user="hello"} 141394562941 (131.68 GB)
telemt_user_octets_to_client{user="hello"} 2255666687691 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 826
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 111339.6 (30h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6362813
telemt_connections_bad_total 550110
telemt_connections_current 1529
telemt_connections_me_current 1529
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 206962
telemt_upstream_connect_attempt_total 51607
telemt_upstream_connect_success_total 51222
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 51358
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1084
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2091
telemt_me_reconnect_success_total 932
telemt_me_reader_eof_total 879
telemt_me_idle_close_by_peer_total 879
telemt_me_route_drop_no_conn_total 2165314
telemt_me_route_drop_channel_closed_total 126
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4726803
telemt_me_endpoint_quarantine_total 785
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 833
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
telemt_me_writers_active_current 47
telemt_desync_total 22745
telemt_desync_full_logged_total 7666
telemt_desync_suppressed_total 15079
telemt_desync_frames_bucket_total{bucket="1_2"} 5550
telemt_desync_frames_bucket_total{bucket="3_10"} 8718
telemt_desync_frames_bucket_total{bucket="gt_10"} 8477
telemt_pool_swap_total 120
telemt_pool_force_close_total 3482
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 37445
telemt_me_writer_removed_unexpected_total 848
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3099
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35211
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3267
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33963
telemt_me_writer_teardown_success_total{mode="normal"} 38310
telemt_me_writer_teardown_noop_total 37457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75501
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75767
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.849231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75767
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 809
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 4722264
telemt_user_connections_current{user="hello"} 1529
telemt_user_octets_from_client{user="hello"} 134694227579 (125.44 GB)
telemt_user_octets_to_client{user="hello"} 2167870087875 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 776
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 111378.6 (30h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20570519
telemt_connections_bad_total 1670661
telemt_connections_current 2610
telemt_connections_me_current 2610
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 617999
telemt_upstream_connect_attempt_total 200405
telemt_upstream_connect_success_total 182278
telemt_upstream_connect_fail_total 16347
telemt_upstream_connect_attempts_per_request{bucket="1"} 198625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43412
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8934
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16347
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65036
telemt_me_reconnect_success_total 2349
telemt_me_reader_eof_total 1479
telemt_me_idle_close_by_peer_total 1478
telemt_me_route_drop_no_conn_total 39535379
telemt_me_route_drop_channel_closed_total 126
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16592386
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 868
telemt_me_single_endpoint_outage_enter_total 135
telemt_me_single_endpoint_outage_exit_total 135
telemt_me_single_endpoint_outage_reconnect_attempt_total 285
telemt_me_single_endpoint_outage_reconnect_success_total 70
telemt_me_single_endpoint_quarantine_bypass_total 285
telemt_me_single_endpoint_shadow_rotate_total 872
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 65
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
telemt_desync_total 32193
telemt_desync_full_logged_total 9683
telemt_desync_suppressed_total 22510
telemt_desync_frames_bucket_total{bucket="1_2"} 6983
telemt_desync_frames_bucket_total{bucket="3_10"} 14283
telemt_desync_frames_bucket_total{bucket="gt_10"} 10927
telemt_pool_swap_total 115
telemt_pool_force_close_total 3714
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 815
telemt_me_draining_writers_reap_progress_total 34969
telemt_me_writer_removed_unexpected_total 2177
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4692
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32195
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3189
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 525
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31255
telemt_me_writer_teardown_success_total{mode="normal"} 36887
telemt_me_writer_teardown_noop_total 34996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71883
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 215.818059
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71883
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 815
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1610
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 546
telemt_user_connections_total{user="hello"} 16725463
telemt_user_connections_current{user="hello"} 2610
telemt_user_octets_from_client{user="hello"} 228347654360 (212.67 GB)
telemt_user_octets_to_client{user="hello"} 1234324576229 (1.12 TB)
telemt_user_msgs_from_client{user="hello"} 395497
telemt_user_msgs_to_client{user="hello"} 785476
telemt_user_unique_ips_current{user="hello"} 1177
telemt_user_unique_ips_recent_window{user="hello"} 338
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 111346.6 (30h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6119147
telemt_connections_bad_total 585660
telemt_connections_current 2037
telemt_connections_me_current 2037
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 128945
telemt_upstream_connect_attempt_total 60305
telemt_upstream_connect_success_total 59611
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 60204
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24584
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_reconnect_attempts_total 69754
telemt_me_reconnect_success_total 1817
telemt_me_reader_eof_total 1600
telemt_me_idle_close_by_peer_total 1599
telemt_me_route_drop_no_conn_total 2401987
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4758812
telemt_me_endpoint_quarantine_total 755
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 846
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 23693
telemt_desync_full_logged_total 8335
telemt_desync_suppressed_total 15358
telemt_desync_frames_bucket_total{bucket="1_2"} 4559
telemt_desync_frames_bucket_total{bucket="3_10"} 9177
telemt_desync_frames_bucket_total{bucket="gt_10"} 9957
telemt_pool_swap_total 115
telemt_pool_force_close_total 3293
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 397
telemt_me_draining_writers_reap_progress_total 39354
telemt_me_writer_removed_unexpected_total 1637
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4019
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37004
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2892
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36061
telemt_me_writer_teardown_success_total{mode="normal"} 41023
telemt_me_writer_teardown_noop_total 39355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80378
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.175629
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80378
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 397
telemt_me_refill_failed_total 4210
telemt_me_writer_restored_same_endpoint_total 1525
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4751518
telemt_user_connections_current{user="hello"} 2037
telemt_user_octets_from_client{user="hello"} 125670175160 (117.04 GB)
telemt_user_octets_to_client{user="hello"} 1940279445750 (1.76 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 953
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 48182.2 (13h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4045459
telemt_connections_bad_total 166877
telemt_connections_current 1459
telemt_connections_me_current 1459
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1632365
telemt_upstream_connect_attempt_total 29042
telemt_upstream_connect_success_total 28856
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 29035
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 45882
telemt_me_reconnect_success_total 990
telemt_me_reader_eof_total 674
telemt_me_idle_close_by_peer_total 674
telemt_me_route_drop_no_conn_total 1033160
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1979758
telemt_me_endpoint_quarantine_total 360
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 374
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10628
telemt_desync_full_logged_total 3680
telemt_desync_suppressed_total 6948
telemt_desync_frames_bucket_total{bucket="1_2"} 1921
telemt_desync_frames_bucket_total{bucket="3_10"} 4077
telemt_desync_frames_bucket_total{bucket="gt_10"} 4630
telemt_pool_swap_total 52
telemt_pool_force_close_total 1548
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 141
telemt_me_draining_writers_reap_progress_total 17936
telemt_me_writer_removed_unexpected_total 747
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1593
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17117
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1342
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16388
telemt_me_writer_teardown_success_total{mode="normal"} 18710
telemt_me_writer_teardown_noop_total 17938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36648
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.498241
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36648
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 141
telemt_me_refill_failed_total 2608
telemt_me_writer_restored_same_endpoint_total 886
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1983290
telemt_user_connections_current{user="hello"} 1459
telemt_user_octets_from_client{user="hello"} 55041254900 (51.26 GB)
telemt_user_octets_to_client{user="hello"} 840992858950 (783.24 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 742
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 29152.7 (8h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 210366
telemt_connections_bad_total 1764
telemt_connections_current 361
telemt_connections_me_current 361
telemt_handshake_timeouts_total 5748
telemt_upstream_connect_attempt_total 14063
telemt_upstream_connect_success_total 14029
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 14061
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8019
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_reconnect_attempts_total 325
telemt_me_reconnect_success_total 184
telemt_me_reader_eof_total 189
telemt_me_idle_close_by_peer_total 189
telemt_me_route_drop_no_conn_total 58493
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185843
telemt_me_endpoint_quarantine_total 288
telemt_me_single_endpoint_shadow_rotate_total 255
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1073
telemt_desync_full_logged_total 276
telemt_desync_suppressed_total 797
telemt_desync_frames_bucket_total{bucket="1_2"} 396
telemt_desync_frames_bucket_total{bucket="3_10"} 406
telemt_desync_frames_bucket_total{bucket="gt_10"} 271
telemt_pool_swap_total 32
telemt_pool_force_close_total 716
telemt_me_writer_close_signal_drop_total 24
telemt_me_draining_writers_reap_progress_total 12707
telemt_me_writer_removed_unexpected_total 182
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 822
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12074
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 714
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11991
telemt_me_writer_teardown_success_total{mode="normal"} 12896
telemt_me_writer_teardown_noop_total 12707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25603
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.056540
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25603
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 24
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 166
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 185513
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 3266459280 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 114977599712 (107.08 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 111350.9 (30h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7435040
telemt_connections_bad_total 748983
telemt_connections_current 1959
telemt_connections_me_current 1959
telemt_handshake_timeouts_total 211814
telemt_upstream_connect_attempt_total 43763
telemt_upstream_connect_success_total 43604
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 43726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21959
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 1599
telemt_me_reconnect_success_total 864
telemt_me_reader_eof_total 848
telemt_me_idle_close_by_peer_total 848
telemt_me_route_drop_no_conn_total 2140859
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5547199
telemt_me_endpoint_quarantine_total 785
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 859
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
telemt_me_writers_active_current 45
telemt_desync_total 21776
telemt_desync_full_logged_total 7134
telemt_desync_suppressed_total 14642
telemt_desync_frames_bucket_total{bucket="1_2"} 5476
telemt_desync_frames_bucket_total{bucket="3_10"} 7885
telemt_desync_frames_bucket_total{bucket="gt_10"} 8415
telemt_pool_swap_total 123
telemt_pool_force_close_total 3287
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 393
telemt_me_draining_writers_reap_progress_total 39484
telemt_me_writer_removed_unexpected_total 817
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3090
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37232
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3199
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36197
telemt_me_writer_teardown_success_total{mode="normal"} 40322
telemt_me_writer_teardown_noop_total 39486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79808
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79808
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.688078
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79808
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 393
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 5522131
telemt_user_connections_current{user="hello"} 1959
telemt_user_octets_from_client{user="hello"} 110418902496 (102.84 GB)
telemt_user_octets_to_client{user="hello"} 2573738448176 (2.34 TB)
telemt_user_unique_ips_current{user="hello"} 856
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 111347.5 (30h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6439669
telemt_connections_bad_total 634092
telemt_connections_current 1874
telemt_connections_me_current 1874
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 174676
telemt_upstream_connect_attempt_total 59600
telemt_upstream_connect_success_total 59152
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 59541
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34378
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23640
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_reconnect_attempts_total 5603
telemt_me_reconnect_success_total 1202
telemt_me_reader_eof_total 1085
telemt_me_idle_close_by_peer_total 1085
telemt_me_seq_mismatch_total 51
telemt_me_route_drop_no_conn_total 2193885
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4913218
telemt_me_endpoint_quarantine_total 880
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 852
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 20395
telemt_desync_full_logged_total 6799
telemt_desync_suppressed_total 13596
telemt_desync_frames_bucket_total{bucket="1_2"} 5218
telemt_desync_frames_bucket_total{bucket="3_10"} 7444
telemt_desync_frames_bucket_total{bucket="gt_10"} 7733
telemt_pool_swap_total 121
telemt_pool_force_close_total 3242
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 38077
telemt_me_writer_removed_unexpected_total 1097
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3622
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35606
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3019
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34835
telemt_me_writer_teardown_success_total{mode="normal"} 39228
telemt_me_writer_teardown_noop_total 38081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77309
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.133685
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77309
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 938
telemt_me_writer_restored_fallback_total 69
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4916154
telemt_user_connections_current{user="hello"} 1874
telemt_user_octets_from_client{user="hello"} 92775251617 (86.40 GB)
telemt_user_octets_to_client{user="hello"} 2102879316912 (1.91 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 818
telemt_user_unique_ips_recent_window{user="hello"} 220
```