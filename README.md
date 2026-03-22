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

# Server Metrics 2026-03-22 02:15:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 18549.3 (5h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 266683
telemt_connections_bad_total 18383
telemt_connections_current 743
telemt_connections_me_current 743
telemt_handshake_timeouts_total 15404
telemt_upstream_connect_attempt_total 7716
telemt_upstream_connect_success_total 7715
telemt_upstream_connect_attempts_per_request{bucket="1"} 7715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4898
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 247
telemt_me_reconnect_success_total 121
telemt_me_reader_eof_total 119
telemt_me_idle_close_by_peer_total 119
telemt_me_route_drop_no_conn_total 49016
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218589
telemt_me_endpoint_quarantine_total 154
telemt_me_single_endpoint_shadow_rotate_total 157
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
telemt_me_writers_active_current 45
telemt_desync_total 1935
telemt_desync_full_logged_total 531
telemt_desync_suppressed_total 1404
telemt_desync_frames_bucket_total{bucket="1_2"} 616
telemt_desync_frames_bucket_total{bucket="3_10"} 711
telemt_desync_frames_bucket_total{bucket="gt_10"} 608
telemt_pool_swap_total 20
telemt_pool_force_close_total 520
telemt_me_writer_close_signal_drop_total 35
telemt_me_draining_writers_reap_progress_total 6944
telemt_me_writer_removed_unexpected_total 119
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 486
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6567
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 515
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6424
telemt_me_writer_teardown_success_total{mode="normal"} 7053
telemt_me_writer_teardown_noop_total 6945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13998
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.300800
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13998
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 35
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 110
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 218189
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 2419294152 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 78336641212 (72.96 GB)
telemt_user_unique_ips_current{user="hello"} 366
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 31915.6 (8h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 767814
telemt_connections_bad_total 44252
telemt_connections_current 399
telemt_connections_me_current 399
telemt_handshake_timeouts_total 28358
telemt_upstream_connect_attempt_total 14776
telemt_upstream_connect_success_total 14537
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 14753
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8105
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_reconnect_attempts_total 1257
telemt_me_reconnect_success_total 468
telemt_me_reader_eof_total 410
telemt_me_idle_close_by_peer_total 410
telemt_me_route_drop_no_conn_total 338630
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 611438
telemt_me_endpoint_quarantine_total 304
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 260
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
telemt_me_writers_active_current 47
telemt_desync_total 2659
telemt_desync_full_logged_total 1523
telemt_desync_suppressed_total 1136
telemt_desync_frames_bucket_total{bucket="1_2"} 563
telemt_desync_frames_bucket_total{bucket="3_10"} 1009
telemt_desync_frames_bucket_total{bucket="gt_10"} 1087
telemt_pool_swap_total 34
telemt_pool_force_close_total 933
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 13090
telemt_me_writer_removed_unexpected_total 390
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1106
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12381
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12157
telemt_me_writer_teardown_success_total{mode="normal"} 13487
telemt_me_writer_teardown_noop_total 13090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26362
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26577
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.654386
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26577
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 344
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 610539
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 10026629064 (9.34 GB)
telemt_user_octets_to_client{user="hello"} 217669258824 (202.72 GB)
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 106775.4 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7691263
telemt_connections_bad_total 625255
telemt_connections_current 1565
telemt_connections_me_current 1565
telemt_handshake_timeouts_total 252653
telemt_upstream_connect_attempt_total 39465
telemt_upstream_connect_success_total 39391
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 39398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21373
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1561
telemt_me_reconnect_success_total 801
telemt_me_reader_eof_total 810
telemt_me_idle_close_by_peer_total 810
telemt_me_route_drop_no_conn_total 4529823
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6233606
telemt_me_endpoint_quarantine_total 686
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 799
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26339
telemt_desync_full_logged_total 8716
telemt_desync_suppressed_total 17623
telemt_desync_frames_bucket_total{bucket="1_2"} 5680
telemt_desync_frames_bucket_total{bucket="3_10"} 10280
telemt_desync_frames_bucket_total{bucket="gt_10"} 10379
telemt_pool_swap_total 115
telemt_pool_force_close_total 3833
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 600
telemt_me_draining_writers_reap_progress_total 36007
telemt_me_writer_removed_unexpected_total 779
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3006
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33324
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32174
telemt_me_writer_teardown_success_total{mode="normal"} 36330
telemt_me_writer_teardown_noop_total 36051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72381
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 157.470040
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72381
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 600
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 711
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6225783
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 106047189168 (98.76 GB)
telemt_user_octets_to_client{user="hello"} 2067516455616 (1.88 TB)
telemt_user_unique_ips_current{user="hello"} 819
telemt_user_unique_ips_recent_window{user="hello"} 184
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 106776.9 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6344071
telemt_connections_bad_total 585640
telemt_connections_current 1516
telemt_connections_me_current 1516
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 209842
telemt_upstream_connect_attempt_total 43489
telemt_upstream_connect_success_total 43102
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 43292
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21110
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1937
telemt_me_reconnect_success_total 867
telemt_me_reader_eof_total 839
telemt_me_idle_close_by_peer_total 839
telemt_me_route_drop_no_conn_total 2251335
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4748246
telemt_me_endpoint_quarantine_total 664
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 821
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
telemt_me_writers_active_current 43
telemt_desync_total 22492
telemt_desync_full_logged_total 7650
telemt_desync_suppressed_total 14842
telemt_desync_frames_bucket_total{bucket="1_2"} 5418
telemt_desync_frames_bucket_total{bucket="3_10"} 8730
telemt_desync_frames_bucket_total{bucket="gt_10"} 8344
telemt_pool_swap_total 116
telemt_pool_force_close_total 3471
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 34523
telemt_me_writer_removed_unexpected_total 824
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2913
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32371
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3258
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31052
telemt_me_writer_teardown_success_total{mode="normal"} 35284
telemt_me_writer_teardown_noop_total 34529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69813
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.265386
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69813
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4670443
telemt_user_connections_current{user="hello"} 1516
telemt_user_octets_from_client{user="hello"} 139909257021 (130.30 GB)
telemt_user_octets_to_client{user="hello"} 2200869965535 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 778
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 106745.0 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6230577
telemt_connections_bad_total 546248
telemt_connections_current 1522
telemt_connections_me_current 1522
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 201522
telemt_upstream_connect_attempt_total 49724
telemt_upstream_connect_success_total 49358
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 49494
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25389
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22448
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1970
telemt_me_reconnect_success_total 897
telemt_me_reader_eof_total 840
telemt_me_idle_close_by_peer_total 840
telemt_me_route_drop_no_conn_total 2144948
telemt_me_route_drop_channel_closed_total 119
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4642146
telemt_me_endpoint_quarantine_total 743
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 799
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
telemt_desync_total 22362
telemt_desync_full_logged_total 7510
telemt_desync_suppressed_total 14852
telemt_desync_frames_bucket_total{bucket="1_2"} 5459
telemt_desync_frames_bucket_total{bucket="3_10"} 8565
telemt_desync_frames_bucket_total{bucket="gt_10"} 8338
telemt_pool_swap_total 115
telemt_pool_force_close_total 3344
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 35782
telemt_me_writer_removed_unexpected_total 812
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2968
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33640
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3129
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32438
telemt_me_writer_teardown_success_total{mode="normal"} 36608
telemt_me_writer_teardown_noop_total 35794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72402
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 26.552937
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72402
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 59
telemt_me_writer_restored_same_endpoint_total 779
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4637798
telemt_user_connections_current{user="hello"} 1522
telemt_user_octets_from_client{user="hello"} 133375131167 (124.22 GB)
telemt_user_octets_to_client{user="hello"} 2118529914195 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 727
telemt_user_unique_ips_recent_window{user="hello"} 181
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 106780.3 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20336788
telemt_connections_bad_total 1597107
telemt_connections_current 2066
telemt_connections_me_current 2066
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 600952
telemt_upstream_connect_attempt_total 194816
telemt_upstream_connect_success_total 176850
telemt_upstream_connect_fail_total 16227
telemt_upstream_connect_attempts_per_request{bucket="1"} 193077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124639
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42077
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8913
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16227
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64839
telemt_me_reconnect_success_total 2300
telemt_me_reader_eof_total 1436
telemt_me_idle_close_by_peer_total 1435
telemt_me_route_drop_no_conn_total 39499423
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16458952
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 838
telemt_me_single_endpoint_outage_enter_total 134
telemt_me_single_endpoint_outage_exit_total 134
telemt_me_single_endpoint_outage_reconnect_attempt_total 284
telemt_me_single_endpoint_outage_reconnect_success_total 69
telemt_me_single_endpoint_quarantine_bypass_total 284
telemt_me_single_endpoint_shadow_rotate_total 837
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 63
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
telemt_desync_total 31881
telemt_desync_full_logged_total 9547
telemt_desync_suppressed_total 22334
telemt_desync_frames_bucket_total{bucket="1_2"} 6907
telemt_desync_frames_bucket_total{bucket="3_10"} 14149
telemt_desync_frames_bucket_total{bucket="gt_10"} 10825
telemt_pool_swap_total 110
telemt_pool_force_close_total 3601
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 792
telemt_me_draining_writers_reap_progress_total 33388
telemt_me_writer_removed_unexpected_total 2136
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4511
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30752
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3078
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29787
telemt_me_writer_teardown_success_total{mode="normal"} 35263
telemt_me_writer_teardown_noop_total 33414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68677
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.657913
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68677
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 792
telemt_me_refill_failed_total 3801
telemt_me_writer_restored_same_endpoint_total 1577
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 16588472
telemt_user_connections_current{user="hello"} 2066
telemt_user_octets_from_client{user="hello"} 213689987806 (199.01 GB)
telemt_user_octets_to_client{user="hello"} 1186241045759 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 1013
telemt_user_unique_ips_recent_window{user="hello"} 220
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 106747.7 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5986179
telemt_connections_bad_total 559830
telemt_connections_current 1602
telemt_connections_me_current 1602
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 125240
telemt_upstream_connect_attempt_total 58244
telemt_upstream_connect_success_total 57567
telemt_upstream_connect_fail_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 58147
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23502
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 348
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 580
telemt_me_reconnect_attempts_total 69643
telemt_me_reconnect_success_total 1781
telemt_me_reader_eof_total 1559
telemt_me_idle_close_by_peer_total 1558
telemt_me_route_drop_no_conn_total 2383807
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4672703
telemt_me_endpoint_quarantine_total 720
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 808
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 23285
telemt_desync_full_logged_total 8200
telemt_desync_suppressed_total 15085
telemt_desync_frames_bucket_total{bucket="1_2"} 4427
telemt_desync_frames_bucket_total{bucket="3_10"} 9015
telemt_desync_frames_bucket_total{bucket="gt_10"} 9843
telemt_pool_swap_total 110
telemt_pool_force_close_total 3179
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 392
telemt_me_draining_writers_reap_progress_total 37497
telemt_me_writer_removed_unexpected_total 1598
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3876
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35249
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34318
telemt_me_writer_teardown_success_total{mode="normal"} 39125
telemt_me_writer_teardown_noop_total 37498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76623
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.114352
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76623
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 392
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1493
telemt_me_writer_restored_fallback_total 33
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4665581
telemt_user_connections_current{user="hello"} 1602
telemt_user_octets_from_client{user="hello"} 124083807480 (115.56 GB)
telemt_user_octets_to_client{user="hello"} 1904949386082 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 811
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 43583.6 (12h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3873279
telemt_connections_bad_total 140403
telemt_connections_current 1170
telemt_connections_me_current 1170
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1580281
telemt_upstream_connect_attempt_total 26694
telemt_upstream_connect_success_total 26520
telemt_upstream_connect_fail_total 166
telemt_upstream_connect_attempts_per_request{bucket="1"} 26686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 74
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 166
telemt_me_reconnect_attempts_total 45802
telemt_me_reconnect_success_total 950
telemt_me_reader_eof_total 631
telemt_me_idle_close_by_peer_total 631
telemt_me_route_drop_no_conn_total 1017503
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1899921
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 335
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10373
telemt_desync_full_logged_total 3578
telemt_desync_suppressed_total 6795
telemt_desync_frames_bucket_total{bucket="1_2"} 1848
telemt_desync_frames_bucket_total{bucket="3_10"} 3981
telemt_desync_frames_bucket_total{bucket="gt_10"} 4544
telemt_pool_swap_total 47
telemt_pool_force_close_total 1446
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 15824
telemt_me_writer_removed_unexpected_total 706
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1489
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15066
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1240
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14378
telemt_me_writer_teardown_success_total{mode="normal"} 16555
telemt_me_writer_teardown_noop_total 15826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32381
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.435672
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32381
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 851
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1903574
telemt_user_connections_current{user="hello"} 1170
telemt_user_octets_from_client{user="hello"} 53694613244 (50.01 GB)
telemt_user_octets_to_client{user="hello"} 811807173578 (756.05 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 24554.5 (6h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190371
telemt_connections_bad_total 1636
telemt_connections_current 316
telemt_connections_me_current 316
telemt_handshake_timeouts_total 5265
telemt_upstream_connect_attempt_total 11782
telemt_upstream_connect_success_total 11754
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 11780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6696
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 240
telemt_me_reconnect_success_total 155
telemt_me_reader_eof_total 158
telemt_me_idle_close_by_peer_total 158
telemt_me_route_drop_no_conn_total 52001
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167762
telemt_me_endpoint_quarantine_total 247
telemt_me_single_endpoint_shadow_rotate_total 217
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1012
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 756
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 27
telemt_pool_force_close_total 604
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 10617
telemt_me_writer_removed_unexpected_total 152
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 702
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10073
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 602
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10013
telemt_me_writer_teardown_success_total{mode="normal"} 10775
telemt_me_writer_teardown_noop_total 10617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21392
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.963919
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21392
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 141
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 167453
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 3053980860 (2.84 GB)
telemt_user_octets_to_client{user="hello"} 101182442744 (94.23 GB)
telemt_user_unique_ips_current{user="hello"} 143
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 106752.1 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7276591
telemt_connections_bad_total 739333
telemt_connections_current 1797
telemt_connections_me_current 1797
telemt_handshake_timeouts_total 207185
telemt_upstream_connect_attempt_total 41743
telemt_upstream_connect_success_total 41587
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 41706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20635
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20911
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 1575
telemt_me_reconnect_success_total 841
telemt_me_reader_eof_total 824
telemt_me_idle_close_by_peer_total 824
telemt_me_route_drop_no_conn_total 2121451
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5452381
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 822
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
telemt_me_writers_active_current 43
telemt_desync_total 21422
telemt_desync_full_logged_total 7022
telemt_desync_suppressed_total 14400
telemt_desync_frames_bucket_total{bucket="1_2"} 5386
telemt_desync_frames_bucket_total{bucket="3_10"} 7746
telemt_desync_frames_bucket_total{bucket="gt_10"} 8290
telemt_pool_swap_total 118
telemt_pool_force_close_total 3169
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 37630
telemt_me_writer_removed_unexpected_total 795
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2971
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35473
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3081
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34461
telemt_me_writer_teardown_success_total{mode="normal"} 38444
telemt_me_writer_teardown_noop_total 37632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76076
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.634029
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76076
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 751
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5427415
telemt_user_connections_current{user="hello"} 1797
telemt_user_octets_from_client{user="hello"} 109151231964 (101.66 GB)
telemt_user_octets_to_client{user="hello"} 2530376655464 (2.30 TB)
telemt_user_unique_ips_current{user="hello"} 810
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 106748.7 (29h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6281076
telemt_connections_bad_total 620374
telemt_connections_current 1484
telemt_connections_me_current 1484
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 172129
telemt_upstream_connect_attempt_total 57493
telemt_upstream_connect_success_total 57063
telemt_upstream_connect_fail_total 370
telemt_upstream_connect_attempts_per_request{bucket="1"} 57433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33295
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 370
telemt_me_reconnect_attempts_total 5552
telemt_me_reconnect_success_total 1154
telemt_me_reader_eof_total 1037
telemt_me_idle_close_by_peer_total 1037
telemt_me_seq_mismatch_total 47
telemt_me_route_drop_no_conn_total 2174551
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4819497
telemt_me_endpoint_quarantine_total 846
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 818
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
telemt_me_writers_active_current 44
telemt_desync_total 20024
telemt_desync_full_logged_total 6661
telemt_desync_suppressed_total 13363
telemt_desync_frames_bucket_total{bucket="1_2"} 5109
telemt_desync_frames_bucket_total{bucket="3_10"} 7300
telemt_desync_frames_bucket_total{bucket="gt_10"} 7615
telemt_pool_swap_total 116
telemt_pool_force_close_total 3128
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 36163
telemt_me_writer_removed_unexpected_total 1050
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3490
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33772
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2905
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33035
telemt_me_writer_teardown_success_total{mode="normal"} 37262
telemt_me_writer_teardown_noop_total 36167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73429
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.071381
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73429
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 900
telemt_me_writer_restored_fallback_total 60
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4822562
telemt_user_connections_current{user="hello"} 1484
telemt_user_octets_from_client{user="hello"} 90652624741 (84.43 GB)
telemt_user_octets_to_client{user="hello"} 2060353211236 (1.87 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 704
telemt_user_unique_ips_recent_window{user="hello"} 143
```