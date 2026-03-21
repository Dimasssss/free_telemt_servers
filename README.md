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

# Server Metrics 2026-03-21 19:37:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 82894.8 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2995927
telemt_connections_bad_total 175042
telemt_connections_current 1184
telemt_connections_me_current 1184
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 91201
telemt_upstream_connect_attempt_total 33967
telemt_upstream_connect_success_total 33824
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 33924
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 1853
telemt_me_reconnect_success_total 743
telemt_me_reader_eof_total 712
telemt_me_idle_close_by_peer_total 712
telemt_me_route_drop_no_conn_total 2597024
telemt_me_route_drop_channel_closed_total 831
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2420973
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 558
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 643
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_warm_current 41
telemt_desync_total 9622
telemt_desync_full_logged_total 3371
telemt_desync_suppressed_total 6251
telemt_desync_frames_bucket_total{bucket="1_2"} 2102
telemt_desync_frames_bucket_total{bucket="3_10"} 3647
telemt_desync_frames_bucket_total{bucket="gt_10"} 3873
telemt_pool_swap_total 89
telemt_pool_force_close_total 2701
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 622
telemt_me_draining_writers_reap_progress_total 27702
telemt_me_writer_removed_unexpected_total 694
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2344
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25796
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2567
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25001
telemt_me_writer_teardown_success_total{mode="normal"} 28140
telemt_me_writer_teardown_noop_total 27710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55850
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 287.734202
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55850
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 622
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 638
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 2420793
telemt_user_connections_current{user="hello"} 1184
telemt_user_octets_from_client{user="hello"} 35856599225 (33.39 GB)
telemt_user_octets_to_client{user="hello"} 603910298478 (562.44 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 454
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 8032.5 (2h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 342673
telemt_connections_bad_total 14219
telemt_connections_current 1616
telemt_connections_me_current 1616
telemt_handshake_timeouts_total 11125
telemt_upstream_connect_attempt_total 3161
telemt_upstream_connect_success_total 3096
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 3151
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 145
telemt_me_reconnect_success_total 104
telemt_me_reader_eof_total 84
telemt_me_idle_close_by_peer_total 84
telemt_me_route_drop_no_conn_total 231026
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283311
telemt_me_endpoint_quarantine_total 63
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 63
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
telemt_me_writers_active_current 48
telemt_desync_total 1170
telemt_desync_full_logged_total 673
telemt_desync_suppressed_total 497
telemt_desync_frames_bucket_total{bucket="1_2"} 221
telemt_desync_frames_bucket_total{bucket="3_10"} 434
telemt_desync_frames_bucket_total{bucket="gt_10"} 515
telemt_pool_swap_total 8
telemt_pool_force_close_total 237
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 2709
telemt_me_writer_removed_unexpected_total 79
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 237
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2556
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 232
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2472
telemt_me_writer_teardown_success_total{mode="normal"} 2793
telemt_me_writer_teardown_noop_total 2709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5502
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.124740
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5502
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 71
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 283006
telemt_user_connections_current{user="hello"} 1616
telemt_user_octets_from_client{user="hello"} 4757841860 (4.43 GB)
telemt_user_octets_to_client{user="hello"} 76794943184 (71.52 GB)
telemt_user_unique_ips_current{user="hello"} 978
telemt_user_unique_ips_recent_window{user="hello"} 395
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 82892.4 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6537974
telemt_connections_bad_total 505396
telemt_connections_current 4438
telemt_connections_me_current 4438
telemt_handshake_timeouts_total 207144
telemt_upstream_connect_attempt_total 29881
telemt_upstream_connect_success_total 29821
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 29827
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16272
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1254
telemt_me_reconnect_success_total 649
telemt_me_reader_eof_total 658
telemt_me_idle_close_by_peer_total 658
telemt_me_route_drop_no_conn_total 4176683
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5389728
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 615
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 41
telemt_desync_total 21895
telemt_desync_full_logged_total 7315
telemt_desync_suppressed_total 14580
telemt_desync_frames_bucket_total{bucket="1_2"} 4602
telemt_desync_frames_bucket_total{bucket="3_10"} 8716
telemt_desync_frames_bucket_total{bucket="gt_10"} 8577
telemt_pool_swap_total 89
telemt_pool_force_close_total 2938
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 481
telemt_me_draining_writers_reap_progress_total 27146
telemt_me_writer_removed_unexpected_total 633
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2346
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25103
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24208
telemt_me_writer_teardown_success_total{mode="normal"} 27449
telemt_me_writer_teardown_noop_total 27183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54632
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 125.737457
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54632
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 481
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 587
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 5383246
telemt_user_connections_current{user="hello"} 4439
telemt_user_octets_from_client{user="hello"} 90243182800 (84.05 GB)
telemt_user_octets_to_client{user="hello"} 1678993857192 (1.53 TB)
telemt_user_unique_ips_current{user="hello"} 1844
telemt_user_unique_ips_recent_window{user="hello"} 523
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 82894.3 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5284108
telemt_connections_bad_total 496504
telemt_connections_current 3926
telemt_connections_me_current 3926
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 174300
telemt_upstream_connect_attempt_total 34077
telemt_upstream_connect_success_total 33764
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 33923
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 540
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1617
telemt_me_reconnect_success_total 677
telemt_me_reader_eof_total 647
telemt_me_idle_close_by_peer_total 647
telemt_me_route_drop_no_conn_total 1841527
telemt_me_route_drop_channel_closed_total 206
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3963502
telemt_me_endpoint_quarantine_total 512
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 627
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
telemt_me_writers_active_current 42
telemt_me_writers_warm_current 38
telemt_desync_total 18534
telemt_desync_full_logged_total 6147
telemt_desync_suppressed_total 12387
telemt_desync_frames_bucket_total{bucket="1_2"} 4498
telemt_desync_frames_bucket_total{bucket="3_10"} 7181
telemt_desync_frames_bucket_total{bucket="gt_10"} 6855
telemt_pool_swap_total 90
telemt_pool_force_close_total 2719
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 303
telemt_me_draining_writers_reap_progress_total 26046
telemt_me_writer_removed_unexpected_total 628
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2263
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24338
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2536
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 183
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23327
telemt_me_writer_teardown_success_total{mode="normal"} 26601
telemt_me_writer_teardown_noop_total 26051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52652
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 38.642375
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52652
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 303
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 577
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 3960917
telemt_user_connections_current{user="hello"} 3926
telemt_user_octets_from_client{user="hello"} 117043233477 (109.01 GB)
telemt_user_octets_to_client{user="hello"} 1793143775927 (1.63 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1493
telemt_user_unique_ips_recent_window{user="hello"} 501
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 82857.9 (23h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5215582
telemt_connections_bad_total 470243
telemt_connections_current 3391
telemt_connections_me_current 3391
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 157105
telemt_upstream_connect_attempt_total 40431
telemt_upstream_connect_success_total 40167
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 40301
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21290
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 326
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1701
telemt_me_reconnect_success_total 737
telemt_me_reader_eof_total 681
telemt_me_idle_close_by_peer_total 681
telemt_me_route_drop_no_conn_total 1901199
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3941781
telemt_me_endpoint_quarantine_total 553
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 617
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
telemt_me_writers_warm_current 20
telemt_desync_total 18417
telemt_desync_full_logged_total 5981
telemt_desync_suppressed_total 12436
telemt_desync_frames_bucket_total{bucket="1_2"} 4585
telemt_desync_frames_bucket_total{bucket="3_10"} 6972
telemt_desync_frames_bucket_total{bucket="gt_10"} 6860
telemt_pool_swap_total 88
telemt_pool_force_close_total 2587
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 319
telemt_me_draining_writers_reap_progress_total 27422
telemt_me_writer_removed_unexpected_total 650
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2348
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25749
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2380
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 207
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24835
telemt_me_writer_teardown_success_total{mode="normal"} 28097
telemt_me_writer_teardown_noop_total 27432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55529
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.135826
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55529
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 319
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 633
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 3944554
telemt_user_connections_current{user="hello"} 3391
telemt_user_octets_from_client{user="hello"} 113797471131 (105.98 GB)
telemt_user_octets_to_client{user="hello"} 1795673028815 (1.63 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1417
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 82912.1 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18195071
telemt_connections_bad_total 1144008
telemt_connections_current 4860
telemt_connections_me_current 4860
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 511614
telemt_upstream_connect_attempt_total 173541
telemt_upstream_connect_success_total 156697
telemt_upstream_connect_fail_total 15492
telemt_upstream_connect_attempts_per_request{bucket="1"} 172189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35004
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8814
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15492
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 4536
telemt_me_reconnect_success_total 1710
telemt_me_reader_eof_total 1165
telemt_me_idle_close_by_peer_total 1164
telemt_me_route_drop_no_conn_total 37172895
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14996897
telemt_me_endpoint_quarantine_total 613
telemt_me_single_endpoint_outage_enter_total 98
telemt_me_single_endpoint_outage_exit_total 98
telemt_me_single_endpoint_outage_reconnect_attempt_total 216
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 216
telemt_me_single_endpoint_shadow_rotate_total 644
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 27305
telemt_desync_full_logged_total 8149
telemt_desync_suppressed_total 19156
telemt_desync_frames_bucket_total{bucket="1_2"} 5855
telemt_desync_frames_bucket_total{bucket="3_10"} 12164
telemt_desync_frames_bucket_total{bucket="gt_10"} 9286
telemt_pool_swap_total 85
telemt_pool_force_close_total 2797
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 632
telemt_me_draining_writers_reap_progress_total 25638
telemt_me_writer_removed_unexpected_total 1617
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3430
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23583
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2354
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 443
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22841
telemt_me_writer_teardown_success_total{mode="normal"} 27013
telemt_me_writer_teardown_noop_total 25654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52667
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 195.748882
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52667
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 632
telemt_me_refill_failed_total 95
telemt_me_writer_restored_same_endpoint_total 1182
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 15115888
telemt_user_connections_current{user="hello"} 4860
telemt_user_octets_from_client{user="hello"} 135887319587 (126.55 GB)
telemt_user_octets_to_client{user="hello"} 932738184127 (868.68 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1840
telemt_user_unique_ips_recent_window{user="hello"} 853
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 82864.7 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5175506
telemt_connections_bad_total 506799
telemt_connections_current 3646
telemt_connections_me_current 3646
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 106350
telemt_upstream_connect_attempt_total 43253
telemt_upstream_connect_success_total 42806
telemt_upstream_connect_fail_total 369
telemt_upstream_connect_attempts_per_request{bucket="1"} 43175
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17695
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 322
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 369
telemt_me_reconnect_attempts_total 3382
telemt_me_reconnect_success_total 1192
telemt_me_reader_eof_total 1167
telemt_me_idle_close_by_peer_total 1167
telemt_me_route_drop_no_conn_total 2188215
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4000881
telemt_me_endpoint_quarantine_total 495
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 614
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_warm_current 17
telemt_desync_total 19708
telemt_desync_full_logged_total 6834
telemt_desync_suppressed_total 12874
telemt_desync_frames_bucket_total{bucket="1_2"} 3798
telemt_desync_frames_bucket_total{bucket="3_10"} 7741
telemt_desync_frames_bucket_total{bucket="gt_10"} 8169
telemt_pool_swap_total 83
telemt_pool_force_close_total 2467
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 299
telemt_me_draining_writers_reap_progress_total 28232
telemt_me_writer_removed_unexpected_total 1132
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2842
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26531
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2127
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 340
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25765
telemt_me_writer_teardown_success_total{mode="normal"} 29373
telemt_me_writer_teardown_noop_total 28233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57606
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.646935
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57606
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 299
telemt_me_refill_failed_total 118
telemt_me_writer_restored_same_endpoint_total 1016
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 3991150
telemt_user_connections_current{user="hello"} 3646
telemt_user_octets_from_client{user="hello"} 107122912102 (99.77 GB)
telemt_user_octets_to_client{user="hello"} 1608552419796 (1.46 TB)
telemt_user_msgs_from_client{user="hello"} 59066
telemt_user_msgs_to_client{user="hello"} 265414
telemt_user_unique_ips_current{user="hello"} 1579
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 19700.5 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2741155
telemt_connections_bad_total 104076
telemt_connections_current 3099
telemt_connections_me_current 3099
telemt_handshake_timeouts_total 1180055
telemt_upstream_connect_attempt_total 6311
telemt_upstream_connect_success_total 6217
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 6305
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_reconnect_attempts_total 644
telemt_me_reconnect_success_total 194
telemt_me_reader_eof_total 179
telemt_me_idle_close_by_peer_total 179
telemt_me_route_drop_no_conn_total 837669
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1294928
telemt_me_endpoint_quarantine_total 95
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 145
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
telemt_me_writers_active_current 41
telemt_desync_total 7076
telemt_desync_full_logged_total 2326
telemt_desync_suppressed_total 4750
telemt_desync_frames_bucket_total{bucket="1_2"} 1288
telemt_desync_frames_bucket_total{bucket="3_10"} 2653
telemt_desync_frames_bucket_total{bucket="gt_10"} 3135
telemt_pool_swap_total 20
telemt_pool_force_close_total 644
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 62
telemt_me_draining_writers_reap_progress_total 5482
telemt_me_writer_removed_unexpected_total 176
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 521
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5142
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 560
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4838
telemt_me_writer_teardown_success_total{mode="normal"} 5663
telemt_me_writer_teardown_noop_total 5482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11145
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.804546
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11145
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 62
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 162
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 1291493
telemt_user_connections_current{user="hello"} 3099
telemt_user_octets_from_client{user="hello"} 39407361664 (36.70 GB)
telemt_user_octets_to_client{user="hello"} 513798513412 (478.51 GB)
telemt_user_unique_ips_current{user="hello"} 1283
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 671.3 (0h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3553
telemt_connections_bad_total 4
telemt_connections_current 422
telemt_connections_me_current 422
telemt_handshake_timeouts_total 67
telemt_upstream_connect_attempt_total 365
telemt_upstream_connect_success_total 364
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 365
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 152
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 941
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3332
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 8
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_desync_total 7
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 3
telemt_desync_frames_bucket_total{bucket="gt_10"} 2
telemt_me_draining_writers_reap_progress_total 249
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 249
telemt_me_writer_teardown_success_total{mode="normal"} 254
telemt_me_writer_teardown_noop_total 249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 503
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.006033
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 503
telemt_me_writer_restored_same_endpoint_total 5
telemt_user_connections_total{user="hello"} 3332
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 117109068 (111.68 MB)
telemt_user_octets_to_client{user="hello"} 3932525324 (3.66 GB)
telemt_user_unique_ips_current{user="hello"} 156
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 82868.9 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6024930
telemt_connections_bad_total 568847
telemt_connections_current 4647
telemt_connections_me_current 4647
telemt_handshake_timeouts_total 180706
telemt_upstream_connect_attempt_total 31654
telemt_upstream_connect_success_total 31527
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 31618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15889
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_reconnect_attempts_total 1349
telemt_me_reconnect_success_total 688
telemt_me_reader_eof_total 660
telemt_me_idle_close_by_peer_total 660
telemt_me_route_drop_no_conn_total 1899024
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 21
telemt_me_route_drop_queue_full_profile_total{profile="high"} 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4680232
telemt_me_endpoint_quarantine_total 552
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 629
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
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 24
telemt_desync_total 17726
telemt_desync_full_logged_total 5852
telemt_desync_suppressed_total 11874
telemt_desync_frames_bucket_total{bucket="1_2"} 4322
telemt_desync_frames_bucket_total{bucket="3_10"} 6498
telemt_desync_frames_bucket_total{bucket="gt_10"} 6906
telemt_pool_swap_total 91
telemt_pool_force_close_total 2467
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 311
telemt_me_draining_writers_reap_progress_total 28393
telemt_me_writer_removed_unexpected_total 645
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2310
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26733
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2397
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25926
telemt_me_writer_teardown_success_total{mode="normal"} 29043
telemt_me_writer_teardown_noop_total 28394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57437
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.052186
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57437
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 311
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 614
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 4656734
telemt_user_connections_current{user="hello"} 4647
telemt_user_octets_from_client{user="hello"} 91107178112 (84.85 GB)
telemt_user_octets_to_client{user="hello"} 2158453880496 (1.96 TB)
telemt_user_unique_ips_current{user="hello"} 1656
telemt_user_unique_ips_recent_window{user="hello"} 545
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 82865.7 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5117045
telemt_connections_bad_total 451258
telemt_connections_current 3698
telemt_connections_me_current 3698
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 150814
telemt_upstream_connect_attempt_total 48044
telemt_upstream_connect_success_total 47692
telemt_upstream_connect_fail_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 47987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17716
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 613
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 295
telemt_me_reconnect_attempts_total 4409
telemt_me_reconnect_success_total 968
telemt_me_reader_eof_total 854
telemt_me_idle_close_by_peer_total 854
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 1956389
telemt_me_route_drop_channel_closed_total 178
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4077311
telemt_me_endpoint_quarantine_total 664
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 628
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_warm_current 17
telemt_desync_total 16193
telemt_desync_full_logged_total 5472
telemt_desync_suppressed_total 10721
telemt_desync_frames_bucket_total{bucket="1_2"} 3983
telemt_desync_frames_bucket_total{bucket="3_10"} 6001
telemt_desync_frames_bucket_total{bucket="gt_10"} 6209
telemt_pool_swap_total 89
telemt_pool_force_close_total 2401
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 302
telemt_me_draining_writers_reap_progress_total 27632
telemt_me_writer_removed_unexpected_total 866
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2751
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25784
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2213
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25231
telemt_me_writer_teardown_success_total{mode="normal"} 28535
telemt_me_writer_teardown_noop_total 27634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56169
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.996371
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56169
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 302
telemt_me_refill_failed_total 196
telemt_me_writer_restored_same_endpoint_total 747
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 4082404
telemt_user_connections_current{user="hello"} 3698
telemt_user_octets_from_client{user="hello"} 75679628613 (70.48 GB)
telemt_user_octets_to_client{user="hello"} 1699703337208 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1534
telemt_user_unique_ips_recent_window{user="hello"} 485
```