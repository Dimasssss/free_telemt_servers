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

# Server Metrics 2026-03-21 22:56:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 6630.9 (1h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115647
telemt_connections_bad_total 8947
telemt_connections_current 638
telemt_connections_me_current 638
telemt_handshake_timeouts_total 5429
telemt_upstream_connect_attempt_total 2593
telemt_upstream_connect_success_total 2592
telemt_upstream_connect_attempts_per_request{bucket="1"} 2592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 68
telemt_me_reconnect_success_total 34
telemt_me_reader_eof_total 35
telemt_me_idle_close_by_peer_total 35
telemt_me_route_drop_no_conn_total 23718
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 93770
telemt_me_endpoint_quarantine_total 43
telemt_me_single_endpoint_shadow_rotate_total 60
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 44
telemt_desync_total 611
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 421
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 192
telemt_desync_frames_bucket_total{bucket="gt_10"} 296
telemt_pool_swap_total 7
telemt_pool_force_close_total 188
telemt_me_writer_close_signal_drop_total 15
telemt_me_draining_writers_reap_progress_total 2284
telemt_me_writer_removed_unexpected_total 33
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 172
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2146
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2096
telemt_me_writer_teardown_success_total{mode="normal"} 2318
telemt_me_writer_teardown_noop_total 2284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4602
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.503685
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4602
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 15
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 31
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 93663
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 1202419536 (1.12 GB)
telemt_user_octets_to_client{user="hello"} 34675599724 (32.29 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 19997.3 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 626422
telemt_connections_bad_total 28574
telemt_connections_current 798
telemt_connections_me_current 798
telemt_handshake_timeouts_total 23325
telemt_upstream_connect_attempt_total 8318
telemt_upstream_connect_success_total 8169
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 8303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4486
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_reconnect_attempts_total 686
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 212
telemt_me_idle_close_by_peer_total 212
telemt_me_route_drop_no_conn_total 318109
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 511005
telemt_me_endpoint_quarantine_total 170
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 162
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
telemt_me_writers_active_current 42
telemt_desync_total 2263
telemt_desync_full_logged_total 1290
telemt_desync_suppressed_total 973
telemt_desync_frames_bucket_total{bucket="1_2"} 474
telemt_desync_frames_bucket_total{bucket="3_10"} 853
telemt_desync_frames_bucket_total{bucket="gt_10"} 936
telemt_pool_swap_total 22
telemt_pool_force_close_total 601
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 7302
telemt_me_writer_removed_unexpected_total 201
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 636
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6865
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6701
telemt_me_writer_teardown_success_total{mode="normal"} 7501
telemt_me_writer_teardown_noop_total 7302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14803
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.192675
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14803
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 175
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 510343
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 8674199276 (8.08 GB)
telemt_user_octets_to_client{user="hello"} 175249011940 (163.21 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 94857.2 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7312916
telemt_connections_bad_total 560416
telemt_connections_current 1513
telemt_connections_me_current 1513
telemt_handshake_timeouts_total 233046
telemt_upstream_connect_attempt_total 34253
telemt_upstream_connect_success_total 34184
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 34191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18584
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1465
telemt_me_reconnect_success_total 719
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 728
telemt_me_route_drop_no_conn_total 4477486
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5983238
telemt_me_endpoint_quarantine_total 600
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 703
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 25367
telemt_desync_full_logged_total 8361
telemt_desync_suppressed_total 17006
telemt_desync_frames_bucket_total{bucket="1_2"} 5446
telemt_desync_frames_bucket_total{bucket="3_10"} 9919
telemt_desync_frames_bucket_total{bucket="gt_10"} 10002
telemt_pool_swap_total 102
telemt_pool_force_close_total 3450
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 560
telemt_me_draining_writers_reap_progress_total 31215
telemt_me_writer_removed_unexpected_total 700
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2662
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28830
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27765
telemt_me_writer_teardown_success_total{mode="normal"} 31492
telemt_me_writer_teardown_noop_total 31259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62751
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.341081
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62751
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 560
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5975879
telemt_user_connections_current{user="hello"} 1513
telemt_user_octets_from_client{user="hello"} 102618155276 (95.57 GB)
telemt_user_octets_to_client{user="hello"} 1944516818656 (1.77 TB)
telemt_user_unique_ips_current{user="hello"} 734
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 94858.6 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6011407
telemt_connections_bad_total 575752
telemt_connections_current 1680
telemt_connections_me_current 1680
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 197365
telemt_upstream_connect_attempt_total 38170
telemt_upstream_connect_success_total 37834
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 38010
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19027
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18237
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1781
telemt_me_reconnect_success_total 747
telemt_me_reader_eof_total 723
telemt_me_idle_close_by_peer_total 723
telemt_me_route_drop_no_conn_total 2117799
telemt_me_route_drop_channel_closed_total 245
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4495987
telemt_me_endpoint_quarantine_total 580
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 726
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
telemt_me_writers_active_current 45
telemt_desync_total 21640
telemt_desync_full_logged_total 7256
telemt_desync_suppressed_total 14384
telemt_desync_frames_bucket_total{bucket="1_2"} 5230
telemt_desync_frames_bucket_total{bucket="3_10"} 8380
telemt_desync_frames_bucket_total{bucket="gt_10"} 8030
telemt_pool_swap_total 104
telemt_pool_force_close_total 3141
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 342
telemt_me_draining_writers_reap_progress_total 29766
telemt_me_writer_removed_unexpected_total 699
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2551
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27847
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2942
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26625
telemt_me_writer_teardown_success_total{mode="normal"} 30398
telemt_me_writer_teardown_noop_total 29772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60170
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.818933
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60170
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 342
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 643
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4453666
telemt_user_connections_current{user="hello"} 1680
telemt_user_octets_from_client{user="hello"} 137016800205 (127.61 GB)
telemt_user_octets_to_client{user="hello"} 2077108384371 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 797
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 94822.6 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5934181
telemt_connections_bad_total 536451
telemt_connections_current 1510
telemt_connections_me_current 1510
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 188117
telemt_upstream_connect_attempt_total 44558
telemt_upstream_connect_success_total 44261
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 44396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19676
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1045
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1787
telemt_me_reconnect_success_total 804
telemt_me_reader_eof_total 751
telemt_me_idle_close_by_peer_total 751
telemt_me_route_drop_no_conn_total 2082161
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4434065
telemt_me_endpoint_quarantine_total 639
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 708
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_desync_total 21512
telemt_desync_full_logged_total 7103
telemt_desync_suppressed_total 14409
telemt_desync_frames_bucket_total{bucket="1_2"} 5293
telemt_desync_frames_bucket_total{bucket="3_10"} 8188
telemt_desync_frames_bucket_total{bucket="gt_10"} 8031
telemt_pool_swap_total 102
telemt_pool_force_close_total 3021
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 363
telemt_me_draining_writers_reap_progress_total 31169
telemt_me_writer_removed_unexpected_total 719
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2627
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29267
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2806
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28148
telemt_me_writer_teardown_success_total{mode="normal"} 31894
telemt_me_writer_teardown_noop_total 31180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63074
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.126929
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63074
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 363
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 695
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4435598
telemt_user_connections_current{user="hello"} 1510
telemt_user_octets_from_client{user="hello"} 130153024359 (121.21 GB)
telemt_user_octets_to_client{user="hello"} 2030847317859 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 754
telemt_user_unique_ips_recent_window{user="hello"} 187
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 94862.0 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19770468
telemt_connections_bad_total 1412533
telemt_connections_current 2446
telemt_connections_me_current 2446
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 565280
telemt_upstream_connect_attempt_total 184302
telemt_upstream_connect_success_total 166954
telemt_upstream_connect_fail_total 15831
telemt_upstream_connect_attempts_per_request{bucket="1"} 182785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8860
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15831
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64034
telemt_me_reconnect_success_total 2042
telemt_me_reader_eof_total 1303
telemt_me_idle_close_by_peer_total 1302
telemt_me_route_drop_no_conn_total 39422177
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16146344
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 709
telemt_me_single_endpoint_outage_enter_total 113
telemt_me_single_endpoint_outage_exit_total 113
telemt_me_single_endpoint_outage_reconnect_attempt_total 241
telemt_me_single_endpoint_outage_reconnect_success_total 55
telemt_me_single_endpoint_quarantine_bypass_total 241
telemt_me_single_endpoint_shadow_rotate_total 735
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 31036
telemt_desync_full_logged_total 9200
telemt_desync_suppressed_total 21836
telemt_desync_frames_bucket_total{bucket="1_2"} 6790
telemt_desync_frames_bucket_total{bucket="3_10"} 13748
telemt_desync_frames_bucket_total{bucket="gt_10"} 10498
telemt_pool_swap_total 97
telemt_pool_force_close_total 3261
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 731
telemt_me_draining_writers_reap_progress_total 29412
telemt_me_writer_removed_unexpected_total 1906
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4003
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27048
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2745
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26151
telemt_me_writer_teardown_success_total{mode="normal"} 31051
telemt_me_writer_teardown_noop_total 29438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60489
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.168054
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60489
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 731
telemt_me_refill_failed_total 3782
telemt_me_writer_restored_same_endpoint_total 1431
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14670
telemt_me_writer_removed_unexpected_minus_restored_total 455
telemt_user_connections_total{user="hello"} 16271084
telemt_user_connections_current{user="hello"} 2446
telemt_user_octets_from_client{user="hello"} 177056947786 (164.90 GB)
telemt_user_octets_to_client{user="hello"} 1076448409682 (1002.52 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1089
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 94829.5 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5741112
telemt_connections_bad_total 535825
telemt_connections_current 1353
telemt_connections_me_current 1353
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 118564
telemt_upstream_connect_attempt_total 52302
telemt_upstream_connect_success_total 51714
telemt_upstream_connect_fail_total 500
telemt_upstream_connect_attempts_per_request{bucket="1"} 52214
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31083
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20294
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 336
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 500
telemt_me_reconnect_attempts_total 65705
telemt_me_reconnect_success_total 1483
telemt_me_reader_eof_total 1278
telemt_me_idle_close_by_peer_total 1278
telemt_me_route_drop_no_conn_total 2341302
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4476206
telemt_me_endpoint_quarantine_total 610
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 711
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
telemt_me_writers_active_current 102
telemt_desync_total 22640
telemt_desync_full_logged_total 7883
telemt_desync_suppressed_total 14757
telemt_desync_frames_bucket_total{bucket="1_2"} 4303
telemt_desync_frames_bucket_total{bucket="3_10"} 8779
telemt_desync_frames_bucket_total{bucket="gt_10"} 9558
telemt_pool_swap_total 97
telemt_pool_force_close_total 2833
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 368
telemt_me_draining_writers_reap_progress_total 32284
telemt_me_writer_removed_unexpected_total 1316
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3334
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30286
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2465
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29451
telemt_me_writer_teardown_success_total{mode="normal"} 33620
telemt_me_writer_teardown_noop_total 32285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65905
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.672712
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65905
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 368
telemt_me_refill_failed_total 3984
telemt_me_writer_restored_same_endpoint_total 1238
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7035
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 4469413
telemt_user_connections_current{user="hello"} 1353
telemt_user_octets_from_client{user="hello"} 120084632760 (111.84 GB)
telemt_user_octets_to_client{user="hello"} 1818486322454 (1.65 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 686
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 31665.3 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3603526
telemt_connections_bad_total 127575
telemt_connections_current 1848
telemt_connections_me_current 1848
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1518205
telemt_upstream_connect_attempt_total 16425
telemt_upstream_connect_success_total 16294
telemt_upstream_connect_fail_total 125
telemt_upstream_connect_attempts_per_request{bucket="1"} 16419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6213
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 125
telemt_me_reconnect_attempts_total 31375
telemt_me_reconnect_success_total 645
telemt_me_reader_eof_total 397
telemt_me_idle_close_by_peer_total 397
telemt_me_route_drop_no_conn_total 981301
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1727015
telemt_me_endpoint_quarantine_total 212
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 237
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 13
telemt_me_floor_swap_idle_failed_total 13
telemt_desync_total 9601
telemt_desync_full_logged_total 3241
telemt_desync_suppressed_total 6360
telemt_desync_frames_bucket_total{bucket="1_2"} 1704
telemt_desync_frames_bucket_total{bucket="3_10"} 3666
telemt_desync_frames_bucket_total{bucket="gt_10"} 4231
telemt_pool_swap_total 34
telemt_pool_force_close_total 1097
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 110
telemt_me_draining_writers_reap_progress_total 9995
telemt_me_writer_removed_unexpected_total 472
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1044
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9438
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 931
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 166
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8898
telemt_me_writer_teardown_success_total{mode="normal"} 10482
telemt_me_writer_teardown_noop_total 9996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 20478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 20478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 20478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 20478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 20478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 20478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 20478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 20478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 20478
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 20478
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.743219
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 20478
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 110
telemt_me_refill_failed_total 1784
telemt_me_writer_restored_same_endpoint_total 562
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 160
telemt_me_async_recovery_trigger_total 3121
telemt_user_connections_total{user="hello"} 1726866
telemt_user_connections_current{user="hello"} 1848
telemt_user_octets_from_client{user="hello"} 50992445524 (47.49 GB)
telemt_user_octets_to_client{user="hello"} 742466478538 (691.48 GB)
telemt_user_msgs_from_client{user="hello"} 43112
telemt_user_msgs_to_client{user="hello"} 113951
telemt_user_unique_ips_current{user="hello"} 886
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 12636.4 (3h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141476
telemt_connections_bad_total 1359
telemt_connections_current 383
telemt_connections_me_current 383
telemt_handshake_timeouts_total 3477
telemt_upstream_connect_attempt_total 5591
telemt_upstream_connect_success_total 5575
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 5590
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2344
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3171
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 118
telemt_me_reconnect_success_total 72
telemt_me_reader_eof_total 73
telemt_me_idle_close_by_peer_total 73
telemt_me_route_drop_no_conn_total 40043
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 122960
telemt_me_endpoint_quarantine_total 100
telemt_me_single_endpoint_shadow_rotate_total 109
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 48
telemt_me_writers_warm_current 10
telemt_desync_total 945
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 710
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 13
telemt_pool_force_close_total 321
telemt_me_writer_close_signal_drop_total 15
telemt_me_draining_writers_reap_progress_total 4942
telemt_me_writer_removed_unexpected_total 71
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 317
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4698
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4621
telemt_me_writer_teardown_success_total{mode="normal"} 5015
telemt_me_writer_teardown_noop_total 4942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9932
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9957
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.624754
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9957
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 15
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 66
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 122781
telemt_user_connections_current{user="hello"} 383
telemt_user_octets_from_client{user="hello"} 2299229404 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 75641535576 (70.45 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 94833.9 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6872750
telemt_connections_bad_total 697208
telemt_connections_current 1911
telemt_connections_me_current 1911
telemt_handshake_timeouts_total 195393
telemt_upstream_connect_attempt_total 36022
telemt_upstream_connect_success_total 35878
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 35985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18037
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 1466
telemt_me_reconnect_success_total 752
telemt_me_reader_eof_total 731
telemt_me_idle_close_by_peer_total 731
telemt_me_route_drop_no_conn_total 2077815
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5229939
telemt_me_endpoint_quarantine_total 635
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 726
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
telemt_me_writers_active_current 44
telemt_desync_total 20074
telemt_desync_full_logged_total 6714
telemt_desync_suppressed_total 13360
telemt_desync_frames_bucket_total{bucket="1_2"} 4873
telemt_desync_frames_bucket_total{bucket="3_10"} 7307
telemt_desync_frames_bucket_total{bucket="gt_10"} 7894
telemt_pool_swap_total 105
telemt_pool_force_close_total 2877
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 32392
telemt_me_writer_removed_unexpected_total 708
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2631
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30482
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2789
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29515
telemt_me_writer_teardown_success_total{mode="normal"} 33113
telemt_me_writer_teardown_noop_total 32394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65507
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.471805
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65507
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 673
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 5205292
telemt_user_connections_current{user="hello"} 1911
telemt_user_octets_from_client{user="hello"} 104671654912 (97.48 GB)
telemt_user_octets_to_client{user="hello"} 2447718947320 (2.23 TB)
telemt_user_unique_ips_current{user="hello"} 823
telemt_user_unique_ips_recent_window{user="hello"} 201
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 94830.6 (26h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5881338
telemt_connections_bad_total 559678
telemt_connections_current 1871
telemt_connections_me_current 1871
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 165025
telemt_upstream_connect_attempt_total 52141
telemt_upstream_connect_success_total 51746
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 52082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19808
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_reconnect_attempts_total 5234
telemt_me_reconnect_success_total 1057
telemt_me_reader_eof_total 933
telemt_me_idle_close_by_peer_total 933
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 2130192
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4599512
telemt_me_endpoint_quarantine_total 741
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 721
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
telemt_me_writers_active_current 45
telemt_desync_total 18859
telemt_desync_full_logged_total 6364
telemt_desync_suppressed_total 12495
telemt_desync_frames_bucket_total{bucket="1_2"} 4693
telemt_desync_frames_bucket_total{bucket="3_10"} 6870
telemt_desync_frames_bucket_total{bucket="gt_10"} 7296
telemt_pool_swap_total 103
telemt_pool_force_close_total 2832
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 31321
telemt_me_writer_removed_unexpected_total 944
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3113
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29195
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2609
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28489
telemt_me_writer_teardown_success_total{mode="normal"} 32308
telemt_me_writer_teardown_noop_total 31325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63633
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.560791
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63633
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 819
telemt_me_writer_restored_fallback_total 50
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4602927
telemt_user_connections_current{user="hello"} 1871
telemt_user_octets_from_client{user="hello"} 87880175181 (81.84 GB)
telemt_user_octets_to_client{user="hello"} 1980923127332 (1.80 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 824
telemt_user_unique_ips_recent_window{user="hello"} 167
```