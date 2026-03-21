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

# Server Metrics 2026-03-21 14:47:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 65491.1 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2281178
telemt_connections_bad_total 112794
telemt_connections_current 1417
telemt_connections_me_current 1417
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 75612
telemt_upstream_connect_attempt_total 28149
telemt_upstream_connect_success_total 28024
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16231
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1634
telemt_me_reconnect_success_total 647
telemt_me_reader_eof_total 619
telemt_me_idle_close_by_peer_total 619
telemt_me_route_drop_no_conn_total 1952711
telemt_me_route_drop_channel_closed_total 608
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1822904
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 462
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 512
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
telemt_me_writers_active_current 43
telemt_desync_total 7135
telemt_desync_full_logged_total 2450
telemt_desync_suppressed_total 4685
telemt_desync_frames_bucket_total{bucket="1_2"} 1570
telemt_desync_frames_bucket_total{bucket="3_10"} 2720
telemt_desync_frames_bucket_total{bucket="gt_10"} 2845
telemt_pool_swap_total 70
telemt_pool_force_close_total 2123
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 476
telemt_me_draining_writers_reap_progress_total 22450
telemt_me_writer_removed_unexpected_total 599
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1918
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20918
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2010
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 113
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20327
telemt_me_writer_teardown_success_total{mode="normal"} 22836
telemt_me_writer_teardown_noop_total 22456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37768
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45292
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.872708
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45292
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 476
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 555
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1824549
telemt_user_connections_current{user="hello"} 1417
telemt_user_octets_from_client{user="hello"} 25986498661 (24.20 GB)
telemt_user_octets_to_client{user="hello"} 451246831606 (420.26 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 5044.4 (1h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 373200
telemt_connections_bad_total 13053
telemt_connections_current 1241
telemt_connections_me_current 1241
telemt_handshake_timeouts_total 12666
telemt_upstream_connect_attempt_total 1916
telemt_upstream_connect_success_total 1903
telemt_upstream_connect_attempts_per_request{bucket="1"} 1903
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 928
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_reconnect_attempts_total 130
telemt_me_reconnect_success_total 44
telemt_me_reader_eof_total 37
telemt_me_idle_close_by_peer_total 37
telemt_me_route_drop_no_conn_total 243220
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330855
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 44
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1348
telemt_desync_full_logged_total 572
telemt_desync_suppressed_total 776
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 528
telemt_desync_frames_bucket_total{bucket="gt_10"} 549
telemt_pool_swap_total 5
telemt_pool_force_close_total 142
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 1432
telemt_me_writer_removed_unexpected_total 34
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 112
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1357
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 137
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1290
telemt_me_writer_teardown_success_total{mode="normal"} 1469
telemt_me_writer_teardown_noop_total 1432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2901
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.763046
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2901
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 323634
telemt_user_connections_current{user="hello"} 1241
telemt_user_octets_from_client{user="hello"} 5588565199 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 84308594435 (78.52 GB)
telemt_user_msgs_from_client{user="hello"} 423
telemt_user_msgs_to_client{user="hello"} 734
telemt_user_unique_ips_current{user="hello"} 711
telemt_user_unique_ips_recent_window{user="hello"} 470
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 65488.7 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4494913
telemt_connections_bad_total 408352
telemt_connections_current 5236
telemt_connections_me_current 5236
telemt_handshake_timeouts_total 166836
telemt_upstream_connect_attempt_total 24475
telemt_upstream_connect_success_total 24424
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24429
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13294
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1073
telemt_me_reconnect_success_total 565
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 2465523
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3664800
telemt_me_endpoint_quarantine_total 419
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 496
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
telemt_me_writers_active_current 40
telemt_desync_total 15141
telemt_desync_full_logged_total 5108
telemt_desync_suppressed_total 10033
telemt_desync_frames_bucket_total{bucket="1_2"} 3230
telemt_desync_frames_bucket_total{bucket="3_10"} 5969
telemt_desync_frames_bucket_total{bucket="gt_10"} 5942
telemt_pool_swap_total 69
telemt_pool_force_close_total 2235
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 349
telemt_me_draining_writers_reap_progress_total 22215
telemt_me_writer_removed_unexpected_total 546
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1942
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20601
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 193
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19980
telemt_me_writer_teardown_success_total{mode="normal"} 22543
telemt_me_writer_teardown_noop_total 22246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44789
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 73.357964
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44789
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 349
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 507
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 3660269
telemt_user_connections_current{user="hello"} 5236
telemt_user_octets_from_client{user="hello"} 59733227552 (55.63 GB)
telemt_user_octets_to_client{user="hello"} 1226973996196 (1.12 TB)
telemt_user_unique_ips_current{user="hello"} 2043
telemt_user_unique_ips_recent_window{user="hello"} 608
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 65490.2 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3672085
telemt_connections_bad_total 404591
telemt_connections_current 3902
telemt_connections_me_current 3902
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 134537
telemt_upstream_connect_attempt_total 28860
telemt_upstream_connect_success_total 28580
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13306
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 483
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1196
telemt_me_reconnect_success_total 562
telemt_me_reader_eof_total 530
telemt_me_idle_close_by_peer_total 530
telemt_me_route_drop_no_conn_total 1142414
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2672343
telemt_me_endpoint_quarantine_total 423
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 499
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
telemt_desync_total 12384
telemt_desync_full_logged_total 4171
telemt_desync_suppressed_total 8213
telemt_desync_frames_bucket_total{bucket="1_2"} 3111
telemt_desync_frames_bucket_total{bucket="3_10"} 4772
telemt_desync_frames_bucket_total{bucket="gt_10"} 4501
telemt_pool_swap_total 71
telemt_pool_force_close_total 2042
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 21412
telemt_me_writer_removed_unexpected_total 514
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1808
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20120
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1907
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 135
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19370
telemt_me_writer_teardown_success_total{mode="normal"} 21928
telemt_me_writer_teardown_noop_total 21413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42563
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43341
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.233227
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43341
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 475
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 2672405
telemt_user_connections_current{user="hello"} 3902
telemt_user_octets_from_client{user="hello"} 50025773093 (46.59 GB)
telemt_user_octets_to_client{user="hello"} 1247961677799 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1485
telemt_user_unique_ips_recent_window{user="hello"} 485
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 65454.1 (18h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3577376
telemt_connections_bad_total 383307
telemt_connections_current 3425
telemt_connections_me_current 3425
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 106790
telemt_upstream_connect_attempt_total 34091
telemt_upstream_connect_success_total 33859
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 33992
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14684
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 849
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1307
telemt_me_reconnect_success_total 635
telemt_me_reader_eof_total 577
telemt_me_idle_close_by_peer_total 577
telemt_me_route_drop_no_conn_total 1105999
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2630175
telemt_me_endpoint_quarantine_total 472
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 491
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
telemt_desync_total 12275
telemt_desync_full_logged_total 4104
telemt_desync_suppressed_total 8171
telemt_desync_frames_bucket_total{bucket="1_2"} 3082
telemt_desync_frames_bucket_total{bucket="3_10"} 4612
telemt_desync_frames_bucket_total{bucket="gt_10"} 4581
telemt_pool_swap_total 69
telemt_pool_force_close_total 1972
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 221
telemt_me_draining_writers_reap_progress_total 22811
telemt_me_writer_removed_unexpected_total 550
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1921
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21475
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 176
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20839
telemt_me_writer_teardown_success_total{mode="normal"} 23396
telemt_me_writer_teardown_noop_total 22816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46212
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.782268
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46212
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 221
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 552
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2634281
telemt_user_connections_current{user="hello"} 3425
telemt_user_octets_from_client{user="hello"} 56962460529 (53.05 GB)
telemt_user_octets_to_client{user="hello"} 1238122588340 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1357
telemt_user_unique_ips_recent_window{user="hello"} 500
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 65493.3 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12254945
telemt_connections_bad_total 807788
telemt_connections_current 5341
telemt_connections_me_current 5341
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 379406
telemt_upstream_connect_attempt_total 115259
telemt_upstream_connect_success_total 105393
telemt_upstream_connect_fail_total 8845
telemt_upstream_connect_attempts_per_request{bucket="1"} 114238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25201
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8845
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 3834
telemt_me_reconnect_success_total 1372
telemt_me_reader_eof_total 959
telemt_me_idle_close_by_peer_total 958
telemt_me_route_drop_no_conn_total 23025424
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10049175
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 513
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
telemt_me_writers_active_current 46
telemt_desync_total 18104
telemt_desync_full_logged_total 5721
telemt_desync_suppressed_total 12383
telemt_desync_frames_bucket_total{bucket="1_2"} 3962
telemt_desync_frames_bucket_total{bucket="3_10"} 7916
telemt_desync_frames_bucket_total{bucket="gt_10"} 6226
telemt_pool_swap_total 66
telemt_pool_force_close_total 2145
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 461
telemt_me_draining_writers_reap_progress_total 21135
telemt_me_writer_removed_unexpected_total 1320
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2803
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19449
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1796
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 349
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18990
telemt_me_writer_teardown_success_total{mode="normal"} 22252
telemt_me_writer_teardown_noop_total 21145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43397
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 167.137112
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43397
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 461
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 10125318
telemt_user_connections_current{user="hello"} 5341
telemt_user_octets_from_client{user="hello"} 73146987337 (68.12 GB)
telemt_user_octets_to_client{user="hello"} 775290352589 (722.05 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 1942
telemt_user_unique_ips_recent_window{user="hello"} 988
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 65460.8 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3607336
telemt_connections_bad_total 408049
telemt_connections_current 3872
telemt_connections_me_current 3872
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 79316
telemt_upstream_connect_attempt_total 27760
telemt_upstream_connect_success_total 27455
telemt_upstream_connect_fail_total 261
telemt_upstream_connect_attempts_per_request{bucket="1"} 27716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14270
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 261
telemt_me_reconnect_attempts_total 2666
telemt_me_reconnect_success_total 964
telemt_me_reader_eof_total 957
telemt_me_idle_close_by_peer_total 957
telemt_me_route_drop_no_conn_total 1497435
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2768016
telemt_me_endpoint_quarantine_total 409
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 492
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
telemt_desync_total 13205
telemt_desync_full_logged_total 4588
telemt_desync_suppressed_total 8617
telemt_desync_frames_bucket_total{bucket="1_2"} 2548
telemt_desync_frames_bucket_total{bucket="3_10"} 5250
telemt_desync_frames_bucket_total{bucket="gt_10"} 5407
telemt_pool_swap_total 65
telemt_pool_force_close_total 1890
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 186
telemt_me_draining_writers_reap_progress_total 23276
telemt_me_writer_removed_unexpected_total 929
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2284
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21951
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 253
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21386
telemt_me_writer_teardown_success_total{mode="normal"} 24235
telemt_me_writer_teardown_noop_total 23277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47512
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.253938
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47512
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 186
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 825
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2751784
telemt_user_connections_current{user="hello"} 3872
telemt_user_octets_from_client{user="hello"} 68976302684 (64.24 GB)
telemt_user_octets_to_client{user="hello"} 1161795314038 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1564
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 2296.6 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 381427
telemt_connections_bad_total 8011
telemt_connections_current 3515
telemt_connections_me_current 3515
telemt_handshake_timeouts_total 198836
telemt_upstream_connect_attempt_total 994
telemt_upstream_connect_success_total 967
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 97
telemt_me_reconnect_success_total 52
telemt_me_reader_eof_total 51
telemt_me_idle_close_by_peer_total 51
telemt_me_route_drop_no_conn_total 148354
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162941
telemt_me_endpoint_quarantine_total 9
telemt_me_single_endpoint_shadow_rotate_total 19
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
telemt_me_writers_active_current 43
telemt_desync_total 693
telemt_desync_full_logged_total 239
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 282
telemt_desync_frames_bucket_total{bucket="gt_10"} 287
telemt_pool_swap_total 1
telemt_pool_force_close_total 54
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 779
telemt_me_writer_removed_unexpected_total 52
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 91
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 740
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 725
telemt_me_writer_teardown_success_total{mode="normal"} 831
telemt_me_writer_teardown_noop_total 779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1610
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.241219
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1610
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 162808
telemt_user_connections_current{user="hello"} 3515
telemt_user_octets_from_client{user="hello"} 3199304684 (2.98 GB)
telemt_user_octets_to_client{user="hello"} 61774683336 (57.53 GB)
telemt_user_unique_ips_current{user="hello"} 1381
telemt_user_unique_ips_recent_window{user="hello"} 581
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 63446.8 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1155768
telemt_connections_bad_total 136472
telemt_connections_current 753
telemt_connections_me_current 753
telemt_handshake_timeouts_total 406032
telemt_upstream_connect_attempt_total 29586
telemt_upstream_connect_success_total 29580
telemt_upstream_connect_attempts_per_request{bucket="1"} 29580
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1248
telemt_me_reconnect_success_total 482
telemt_me_reader_eof_total 481
telemt_me_idle_close_by_peer_total 481
telemt_me_route_drop_no_conn_total 249249
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 541209
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 534
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 3451
telemt_desync_full_logged_total 1269
telemt_desync_suppressed_total 2182
telemt_desync_frames_bucket_total{bucket="1_2"} 629
telemt_desync_frames_bucket_total{bucket="3_10"} 1233
telemt_desync_frames_bucket_total{bucket="gt_10"} 1589
telemt_pool_swap_total 70
telemt_pool_force_close_total 1603
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 26542
telemt_me_writer_removed_unexpected_total 454
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1947
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25061
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24939
telemt_me_writer_teardown_success_total{mode="normal"} 27008
telemt_me_writer_teardown_noop_total 26542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 52911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53550
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.928634
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53550
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 393
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 540902
telemt_user_connections_current{user="hello"} 753
telemt_user_octets_from_client{user="hello"} 11202225951 (10.43 GB)
telemt_user_octets_to_client{user="hello"} 205762849945 (191.63 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 95
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 65465.1 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3950199
telemt_connections_bad_total 361251
telemt_connections_current 4737
telemt_connections_me_current 4737
telemt_handshake_timeouts_total 124818
telemt_upstream_connect_attempt_total 26338
telemt_upstream_connect_success_total 26228
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 26304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13152
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 1062
telemt_me_reconnect_success_total 596
telemt_me_reader_eof_total 557
telemt_me_idle_close_by_peer_total 557
telemt_me_route_drop_no_conn_total 1195649
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3140467
telemt_me_endpoint_quarantine_total 483
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 499
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
telemt_desync_total 12364
telemt_desync_full_logged_total 4095
telemt_desync_suppressed_total 8269
telemt_desync_frames_bucket_total{bucket="1_2"} 2915
telemt_desync_frames_bucket_total{bucket="3_10"} 4611
telemt_desync_frames_bucket_total{bucket="gt_10"} 4838
telemt_pool_swap_total 72
telemt_pool_force_close_total 1878
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 209
telemt_me_draining_writers_reap_progress_total 23642
telemt_me_writer_removed_unexpected_total 547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1866
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22323
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1841
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21764
telemt_me_writer_teardown_success_total{mode="normal"} 24189
telemt_me_writer_teardown_noop_total 23642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47831
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.529292
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47831
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 209
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 527
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 3132396
telemt_user_connections_current{user="hello"} 4737
telemt_user_octets_from_client{user="hello"} 64344445008 (59.93 GB)
telemt_user_octets_to_client{user="hello"} 1478492008316 (1.34 TB)
telemt_user_unique_ips_current{user="hello"} 1652
telemt_user_unique_ips_recent_window{user="hello"} 625
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 65461.9 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3525669
telemt_connections_bad_total 307801
telemt_connections_current 3949
telemt_connections_me_current 3949
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 105278
telemt_upstream_connect_attempt_total 42743
telemt_upstream_connect_success_total 42456
telemt_upstream_connect_fail_total 236
telemt_upstream_connect_attempts_per_request{bucket="1"} 42692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 600
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 236
telemt_me_reconnect_attempts_total 3626
telemt_me_reconnect_success_total 805
telemt_me_reader_eof_total 711
telemt_me_idle_close_by_peer_total 711
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1274783
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2835839
telemt_me_endpoint_quarantine_total 548
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 498
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
telemt_desync_total 10991
telemt_desync_full_logged_total 3730
telemt_desync_suppressed_total 7261
telemt_desync_frames_bucket_total{bucket="1_2"} 2738
telemt_desync_frames_bucket_total{bucket="3_10"} 4080
telemt_desync_frames_bucket_total{bucket="gt_10"} 4173
telemt_pool_swap_total 70
telemt_pool_force_close_total 1815
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 202
telemt_me_draining_writers_reap_progress_total 22999
telemt_me_writer_removed_unexpected_total 724
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2217
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21537
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1670
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 145
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21184
telemt_me_writer_teardown_success_total{mode="normal"} 23754
telemt_me_writer_teardown_noop_total 23000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46754
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.828132
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46754
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 202
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 625
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2844662
telemt_user_connections_current{user="hello"} 3949
telemt_user_octets_from_client{user="hello"} 51153926993 (47.64 GB)
telemt_user_octets_to_client{user="hello"} 1224093407788 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1548
telemt_user_unique_ips_recent_window{user="hello"} 567
```