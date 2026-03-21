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

# Server Metrics 2026-03-21 14:32:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 64577.0 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2229417
telemt_connections_bad_total 110074
telemt_connections_current 1510
telemt_connections_me_current 1510
telemt_handshake_timeouts_total 75130
telemt_upstream_connect_attempt_total 24831
telemt_upstream_connect_success_total 24706
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 24788
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8732
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1454
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 597
telemt_me_idle_close_by_peer_total 597
telemt_me_route_drop_no_conn_total 1891449
telemt_me_route_drop_channel_closed_total 596
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1780529
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 450
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 506
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
telemt_me_writers_active_current 46
telemt_desync_total 7021
telemt_desync_full_logged_total 2401
telemt_desync_suppressed_total 4620
telemt_desync_frames_bucket_total{bucket="1_2"} 1558
telemt_desync_frames_bucket_total{bucket="3_10"} 2679
telemt_desync_frames_bucket_total{bucket="gt_10"} 2784
telemt_pool_swap_total 69
telemt_pool_force_close_total 2119
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 453
telemt_me_draining_writers_reap_progress_total 22204
telemt_me_writer_removed_unexpected_total 578
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1870
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20702
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2010
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20085
telemt_me_writer_teardown_success_total{mode="normal"} 22572
telemt_me_writer_teardown_noop_total 22210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44782
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 203.972461
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44782
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 453
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1779141
telemt_user_connections_current{user="hello"} 1510
telemt_user_octets_from_client{user="hello"} 25613119859 (23.85 GB)
telemt_user_octets_to_client{user="hello"} 443268551839 (412.83 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 569
telemt_user_unique_ips_recent_window{user="hello"} 206
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 4130.4 (1h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 324816
telemt_connections_bad_total 11044
telemt_connections_current 3060
telemt_connections_me_current 3060
telemt_handshake_timeouts_total 10454
telemt_upstream_connect_attempt_total 1547
telemt_upstream_connect_success_total 1538
telemt_upstream_connect_attempts_per_request{bucket="1"} 1538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 113
telemt_me_reconnect_success_total 29
telemt_me_reader_eof_total 27
telemt_me_idle_close_by_peer_total 27
telemt_me_route_drop_no_conn_total 214976
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 289755
telemt_me_endpoint_quarantine_total 28
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 35
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1172
telemt_desync_full_logged_total 485
telemt_desync_suppressed_total 687
telemt_desync_frames_bucket_total{bucket="1_2"} 236
telemt_desync_frames_bucket_total{bucket="3_10"} 456
telemt_desync_frames_bucket_total{bucket="gt_10"} 480
telemt_pool_swap_total 4
telemt_pool_force_close_total 112
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 1103
telemt_me_writer_removed_unexpected_total 25
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 85
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1045
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 107
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 991
telemt_me_writer_teardown_success_total{mode="normal"} 1130
telemt_me_writer_teardown_noop_total 1103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2233
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.729537
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2233
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 283274
telemt_user_connections_current{user="hello"} 3060
telemt_user_octets_from_client{user="hello"} 4893519223 (4.56 GB)
telemt_user_octets_to_client{user="hello"} 73290258779 (68.26 GB)
telemt_user_msgs_from_client{user="hello"} 423
telemt_user_msgs_to_client{user="hello"} 734
telemt_user_unique_ips_current{user="hello"} 1472
telemt_user_unique_ips_recent_window{user="hello"} 521
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 64574.8 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4401937
telemt_connections_bad_total 407020
telemt_connections_current 4194
telemt_connections_me_current 4194
telemt_handshake_timeouts_total 164729
telemt_upstream_connect_attempt_total 24257
telemt_upstream_connect_success_total 24211
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13181
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 987
telemt_me_reconnect_success_total 551
telemt_me_reader_eof_total 552
telemt_me_idle_close_by_peer_total 552
telemt_me_route_drop_no_conn_total 2397032
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3579751
telemt_me_endpoint_quarantine_total 408
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 492
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
telemt_me_writers_active_current 42
telemt_desync_total 14845
telemt_desync_full_logged_total 5009
telemt_desync_suppressed_total 9836
telemt_desync_frames_bucket_total{bucket="1_2"} 3150
telemt_desync_frames_bucket_total{bucket="3_10"} 5840
telemt_desync_frames_bucket_total{bucket="gt_10"} 5855
telemt_pool_swap_total 68
telemt_pool_force_close_total 2195
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 22009
telemt_me_writer_removed_unexpected_total 533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20413
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2003
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19814
telemt_me_writer_teardown_success_total{mode="normal"} 22333
telemt_me_writer_teardown_noop_total 22038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42072
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44371
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 70.938664
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44371
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 501
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 3575367
telemt_user_connections_current{user="hello"} 4194
telemt_user_octets_from_client{user="hello"} 58215452404 (54.22 GB)
telemt_user_octets_to_client{user="hello"} 1203630718152 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 1676
telemt_user_unique_ips_recent_window{user="hello"} 635
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 64576.3 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3592688
telemt_connections_bad_total 399278
telemt_connections_current 3932
telemt_connections_me_current 3932
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 131899
telemt_upstream_connect_attempt_total 28600
telemt_upstream_connect_success_total 28322
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 28458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13163
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 481
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1193
telemt_me_reconnect_success_total 559
telemt_me_reader_eof_total 526
telemt_me_idle_close_by_peer_total 526
telemt_me_route_drop_no_conn_total 1117732
telemt_me_route_drop_channel_closed_total 87
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2607905
telemt_me_endpoint_quarantine_total 416
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 493
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 12051
telemt_desync_full_logged_total 4070
telemt_desync_suppressed_total 7981
telemt_desync_frames_bucket_total{bucket="1_2"} 3031
telemt_desync_frames_bucket_total{bucket="3_10"} 4647
telemt_desync_frames_bucket_total{bucket="gt_10"} 4373
telemt_pool_swap_total 70
telemt_pool_force_close_total 2006
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 183
telemt_me_draining_writers_reap_progress_total 21176
telemt_me_writer_removed_unexpected_total 510
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1792
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19901
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19170
telemt_me_writer_teardown_success_total{mode="normal"} 21693
telemt_me_writer_teardown_noop_total 21177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42870
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.801362
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42870
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 183
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 472
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 2608066
telemt_user_connections_current{user="hello"} 3932
telemt_user_octets_from_client{user="hello"} 48820174889 (45.47 GB)
telemt_user_octets_to_client{user="hello"} 1218239253171 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1512
telemt_user_unique_ips_recent_window{user="hello"} 515
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 64540.2 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3492770
telemt_connections_bad_total 372749
telemt_connections_current 3389
telemt_connections_me_current 3389
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 103606
telemt_upstream_connect_attempt_total 33811
telemt_upstream_connect_success_total 33579
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 33712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14539
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 848
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1292
telemt_me_reconnect_success_total 630
telemt_me_reader_eof_total 574
telemt_me_idle_close_by_peer_total 574
telemt_me_route_drop_no_conn_total 1076936
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2566434
telemt_me_endpoint_quarantine_total 467
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 485
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
telemt_desync_total 12012
telemt_desync_full_logged_total 4013
telemt_desync_suppressed_total 7999
telemt_desync_frames_bucket_total{bucket="1_2"} 3019
telemt_desync_frames_bucket_total{bucket="3_10"} 4516
telemt_desync_frames_bucket_total{bucket="gt_10"} 4477
telemt_pool_swap_total 68
telemt_pool_force_close_total 1941
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 220
telemt_me_draining_writers_reap_progress_total 22554
telemt_me_writer_removed_unexpected_total 547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1902
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21234
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1767
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20613
telemt_me_writer_teardown_success_total{mode="normal"} 23136
telemt_me_writer_teardown_noop_total 22559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45695
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.759361
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45695
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 220
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 549
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2570639
telemt_user_connections_current{user="hello"} 3389
telemt_user_octets_from_client{user="hello"} 55624811429 (51.80 GB)
telemt_user_octets_to_client{user="hello"} 1207602087616 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1349
telemt_user_unique_ips_recent_window{user="hello"} 540
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 64579.4 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11959841
telemt_connections_bad_total 794850
telemt_connections_current 5331
telemt_connections_me_current 5331
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 372302
telemt_upstream_connect_attempt_total 114973
telemt_upstream_connect_success_total 105114
telemt_upstream_connect_fail_total 8843
telemt_upstream_connect_attempts_per_request{bucket="1"} 113957
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73925
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25040
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8843
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3826
telemt_me_reconnect_success_total 1364
telemt_me_reader_eof_total 951
telemt_me_idle_close_by_peer_total 950
telemt_me_route_drop_no_conn_total 22281379
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9802671
telemt_me_endpoint_quarantine_total 502
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 507
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_desync_total 17833
telemt_desync_full_logged_total 5636
telemt_desync_suppressed_total 12197
telemt_desync_frames_bucket_total{bucket="1_2"} 3903
telemt_desync_frames_bucket_total{bucket="3_10"} 7782
telemt_desync_frames_bucket_total{bucket="gt_10"} 6148
telemt_pool_swap_total 65
telemt_pool_force_close_total 2102
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 453
telemt_me_draining_writers_reap_progress_total 20875
telemt_me_writer_removed_unexpected_total 1313
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2782
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19216
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1753
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 349
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18773
telemt_me_writer_teardown_success_total{mode="normal"} 21998
telemt_me_writer_teardown_noop_total 20885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42660
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42883
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 165.666543
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42883
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 453
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 948
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 9878955
telemt_user_connections_current{user="hello"} 5331
telemt_user_octets_from_client{user="hello"} 71969418753 (67.03 GB)
telemt_user_octets_to_client{user="hello"} 764994088425 (712.46 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 1945
telemt_user_unique_ips_recent_window{user="hello"} 1060
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 64547.1 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3522026
telemt_connections_bad_total 397748
telemt_connections_current 3658
telemt_connections_me_current 3658
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 77500
telemt_upstream_connect_attempt_total 27497
telemt_upstream_connect_success_total 27195
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 27455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14129
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_reconnect_attempts_total 2664
telemt_me_reconnect_success_total 962
telemt_me_reader_eof_total 955
telemt_me_idle_close_by_peer_total 955
telemt_me_route_drop_no_conn_total 1442315
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2699810
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 486
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
telemt_me_writers_active_current 44
telemt_desync_total 12902
telemt_desync_full_logged_total 4486
telemt_desync_suppressed_total 8416
telemt_desync_frames_bucket_total{bucket="1_2"} 2502
telemt_desync_frames_bucket_total{bucket="3_10"} 5124
telemt_desync_frames_bucket_total{bucket="gt_10"} 5276
telemt_pool_swap_total 64
telemt_pool_force_close_total 1860
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 183
telemt_me_draining_writers_reap_progress_total 23038
telemt_me_writer_removed_unexpected_total 927
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2263
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21732
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1612
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21178
telemt_me_writer_teardown_success_total{mode="normal"} 23995
telemt_me_writer_teardown_noop_total 23039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47034
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.195731
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47034
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 183
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2683702
telemt_user_connections_current{user="hello"} 3658
telemt_user_octets_from_client{user="hello"} 62789133440 (58.48 GB)
telemt_user_octets_to_client{user="hello"} 1141900118510 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1449
telemt_user_unique_ips_recent_window{user="hello"} 529
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 1382.8 (0h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 225812
telemt_connections_bad_total 4413
telemt_connections_current 3864
telemt_connections_me_current 3864
telemt_handshake_timeouts_total 116703
telemt_upstream_connect_attempt_total 594
telemt_upstream_connect_success_total 575
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 63
telemt_me_reconnect_success_total 50
telemt_me_reader_eof_total 47
telemt_me_idle_close_by_peer_total 47
telemt_me_route_drop_no_conn_total 77951
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95751
telemt_me_endpoint_quarantine_total 4
telemt_me_single_endpoint_shadow_rotate_total 13
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
telemt_me_writers_active_current 87
telemt_desync_total 410
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 270
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 166
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 357
telemt_me_writer_removed_unexpected_total 48
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 61
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 344
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 357
telemt_me_writer_teardown_success_total{mode="normal"} 405
telemt_me_writer_teardown_noop_total 357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 762
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.003763
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 762
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 95773
telemt_user_connections_current{user="hello"} 3864
telemt_user_octets_from_client{user="hello"} 1169970316 (1.09 GB)
telemt_user_octets_to_client{user="hello"} 37740730056 (35.15 GB)
telemt_user_unique_ips_current{user="hello"} 1517
telemt_user_unique_ips_recent_window{user="hello"} 560
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 62532.8 (17h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1138545
telemt_connections_bad_total 136079
telemt_connections_current 818
telemt_connections_me_current 818
telemt_handshake_timeouts_total 401550
telemt_upstream_connect_attempt_total 29212
telemt_upstream_connect_success_total 29207
telemt_upstream_connect_attempts_per_request{bucket="1"} 29207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1231
telemt_me_reconnect_success_total 481
telemt_me_reader_eof_total 479
telemt_me_idle_close_by_peer_total 479
telemt_me_route_drop_no_conn_total 243727
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529483
telemt_me_endpoint_quarantine_total 570
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 526
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 3397
telemt_desync_full_logged_total 1253
telemt_desync_suppressed_total 2144
telemt_desync_frames_bucket_total{bucket="1_2"} 616
telemt_desync_frames_bucket_total{bucket="3_10"} 1218
telemt_desync_frames_bucket_total{bucket="gt_10"} 1563
telemt_pool_swap_total 69
telemt_pool_force_close_total 1578
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 108
telemt_me_draining_writers_reap_progress_total 26179
telemt_me_writer_removed_unexpected_total 452
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1926
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24717
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24601
telemt_me_writer_teardown_success_total{mode="normal"} 26643
telemt_me_writer_teardown_noop_total 26179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52822
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.626502
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52822
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 108
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 392
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 529211
telemt_user_connections_current{user="hello"} 818
telemt_user_octets_from_client{user="hello"} 10851838927 (10.11 GB)
telemt_user_octets_to_client{user="hello"} 201130570169 (187.32 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 98
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 64551.3 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3854943
telemt_connections_bad_total 353583
telemt_connections_current 4516
telemt_connections_me_current 4516
telemt_handshake_timeouts_total 121122
telemt_upstream_connect_attempt_total 26040
telemt_upstream_connect_success_total 25932
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 26007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12996
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_reconnect_attempts_total 1057
telemt_me_reconnect_success_total 591
telemt_me_reader_eof_total 552
telemt_me_idle_close_by_peer_total 552
telemt_me_route_drop_no_conn_total 1164003
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3061282
telemt_me_endpoint_quarantine_total 478
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 495
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
telemt_me_writers_active_current 45
telemt_desync_total 12028
telemt_desync_full_logged_total 3988
telemt_desync_suppressed_total 8040
telemt_desync_frames_bucket_total{bucket="1_2"} 2844
telemt_desync_frames_bucket_total{bucket="3_10"} 4488
telemt_desync_frames_bucket_total{bucket="gt_10"} 4696
telemt_pool_swap_total 71
telemt_pool_force_close_total 1848
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 203
telemt_me_draining_writers_reap_progress_total 23373
telemt_me_writer_removed_unexpected_total 542
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1839
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22076
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1812
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21525
telemt_me_writer_teardown_success_total{mode="normal"} 23915
telemt_me_writer_teardown_noop_total 23373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47244
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47288
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.409757
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47288
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 203
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 523
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 3053345
telemt_user_connections_current{user="hello"} 4516
telemt_user_octets_from_client{user="hello"} 63003391296 (58.68 GB)
telemt_user_octets_to_client{user="hello"} 1439717142936 (1.31 TB)
telemt_user_unique_ips_current{user="hello"} 1512
telemt_user_unique_ips_recent_window{user="hello"} 623
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 64548.7 (17h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3449531
telemt_connections_bad_total 303141
telemt_connections_current 4226
telemt_connections_me_current 4226
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 100785
telemt_upstream_connect_attempt_total 42383
telemt_upstream_connect_success_total 42097
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 42332
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14788
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 596
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_reconnect_attempts_total 3625
telemt_me_reconnect_success_total 804
telemt_me_reader_eof_total 710
telemt_me_idle_close_by_peer_total 710
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1242401
telemt_me_route_drop_channel_closed_total 91
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2772617
telemt_me_endpoint_quarantine_total 536
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 493
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
telemt_me_writers_active_current 89
telemt_desync_total 10726
telemt_desync_full_logged_total 3650
telemt_desync_suppressed_total 7076
telemt_desync_frames_bucket_total{bucket="1_2"} 2679
telemt_desync_frames_bucket_total{bucket="3_10"} 3976
telemt_desync_frames_bucket_total{bucket="gt_10"} 4071
telemt_pool_swap_total 69
telemt_pool_force_close_total 1769
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 22603
telemt_me_writer_removed_unexpected_total 723
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2185
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21172
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1648
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20834
telemt_me_writer_teardown_success_total{mode="normal"} 23357
telemt_me_writer_teardown_noop_total 22604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45961
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.490480
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45961
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 624
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2781537
telemt_user_connections_current{user="hello"} 4226
telemt_user_octets_from_client{user="hello"} 50289194549 (46.84 GB)
telemt_user_octets_to_client{user="hello"} 1196678363640 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1716
telemt_user_unique_ips_recent_window{user="hello"} 509
```