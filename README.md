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

# Server Metrics 2026-03-22 03:47:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 24062.9 (6h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368831
telemt_connections_bad_total 23991
telemt_connections_current 1178
telemt_connections_me_current 1178
telemt_handshake_timeouts_total 20460
telemt_upstream_connect_attempt_total 10072
telemt_upstream_connect_success_total 10071
telemt_upstream_connect_attempts_per_request{bucket="1"} 10071
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3587
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 10
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 283
telemt_me_reconnect_success_total 156
telemt_me_reader_eof_total 152
telemt_me_idle_close_by_peer_total 152
telemt_me_route_drop_no_conn_total 71852
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305139
telemt_me_endpoint_quarantine_total 192
telemt_me_single_endpoint_shadow_rotate_total 202
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
telemt_me_writers_active_current 47
telemt_desync_total 2788
telemt_desync_full_logged_total 755
telemt_desync_suppressed_total 2033
telemt_desync_frames_bucket_total{bucket="1_2"} 952
telemt_desync_frames_bucket_total{bucket="3_10"} 1050
telemt_desync_frames_bucket_total{bucket="gt_10"} 786
telemt_pool_swap_total 26
telemt_pool_force_close_total 682
telemt_me_writer_close_signal_drop_total 49
telemt_me_draining_writers_reap_progress_total 9092
telemt_me_writer_removed_unexpected_total 150
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 608
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8626
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 677
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8410
telemt_me_writer_teardown_success_total{mode="normal"} 9234
telemt_me_writer_teardown_noop_total 9093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18327
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.540857
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18327
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 49
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 141
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 304421
telemt_user_connections_current{user="hello"} 1178
telemt_user_octets_from_client{user="hello"} 3978814248 (3.71 GB)
telemt_user_octets_to_client{user="hello"} 104923615188 (97.72 GB)
telemt_user_unique_ips_current{user="hello"} 424
telemt_user_unique_ips_recent_window{user="hello"} 128
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 37429.8 (10h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840365
telemt_connections_bad_total 54913
telemt_connections_current 567
telemt_connections_me_current 567
telemt_handshake_timeouts_total 30462
telemt_upstream_connect_attempt_total 17546
telemt_upstream_connect_success_total 17277
telemt_upstream_connect_fail_total 246
telemt_upstream_connect_attempts_per_request{bucket="1"} 17523
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 246
telemt_me_reconnect_attempts_total 1493
telemt_me_reconnect_success_total 542
telemt_me_reader_eof_total 480
telemt_me_idle_close_by_peer_total 480
telemt_me_route_drop_no_conn_total 349691
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 665157
telemt_me_endpoint_quarantine_total 353
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 20
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 20
telemt_me_single_endpoint_shadow_rotate_total 304
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_desync_total 2839
telemt_desync_full_logged_total 1635
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 598
telemt_desync_frames_bucket_total{bucket="3_10"} 1079
telemt_desync_frames_bucket_total{bucket="gt_10"} 1162
telemt_pool_swap_total 40
telemt_pool_force_close_total 1076
telemt_me_writer_close_signal_drop_total 75
telemt_me_draining_writers_reap_progress_total 15551
telemt_me_writer_removed_unexpected_total 457
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1293
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14725
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1054
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14475
telemt_me_writer_teardown_success_total{mode="normal"} 16018
telemt_me_writer_teardown_noop_total 15551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31569
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.795637
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31569
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 75
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 402
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 664181
telemt_user_connections_current{user="hello"} 567
telemt_user_octets_from_client{user="hello"} 10805419836 (10.06 GB)
telemt_user_octets_to_client{user="hello"} 237505430200 (221.19 GB)
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 112289.7 (31h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7886212
telemt_connections_bad_total 653437
telemt_connections_current 1990
telemt_connections_me_current 1990
telemt_handshake_timeouts_total 259608
telemt_upstream_connect_attempt_total 41886
telemt_upstream_connect_success_total 41810
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 41817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22717
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1622
telemt_me_reconnect_success_total 841
telemt_me_reader_eof_total 850
telemt_me_idle_close_by_peer_total 850
telemt_me_route_drop_no_conn_total 4557721
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6370569
telemt_me_endpoint_quarantine_total 724
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 842
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
telemt_me_writers_active_current 45
telemt_desync_total 26760
telemt_desync_full_logged_total 8882
telemt_desync_suppressed_total 17878
telemt_desync_frames_bucket_total{bucket="1_2"} 5779
telemt_desync_frames_bucket_total{bucket="3_10"} 10453
telemt_desync_frames_bucket_total{bucket="gt_10"} 10528
telemt_pool_swap_total 121
telemt_pool_force_close_total 3991
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 612
telemt_me_draining_writers_reap_progress_total 38216
telemt_me_writer_removed_unexpected_total 818
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3182
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35387
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3751
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 240
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34225
telemt_me_writer_teardown_success_total{mode="normal"} 38569
telemt_me_writer_teardown_noop_total 38260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76829
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 162.398787
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76829
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 612
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 749
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6362580
telemt_user_connections_current{user="hello"} 1990
telemt_user_octets_from_client{user="hello"} 108461650504 (101.01 GB)
telemt_user_octets_to_client{user="hello"} 2130507592916 (1.94 TB)
telemt_user_unique_ips_current{user="hello"} 975
telemt_user_unique_ips_recent_window{user="hello"} 251
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 112291.1 (31h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6523076
telemt_connections_bad_total 591406
telemt_connections_current 2061
telemt_connections_me_current 2061
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 216633
telemt_upstream_connect_attempt_total 45837
telemt_upstream_connect_success_total 45444
telemt_upstream_connect_fail_total 196
telemt_upstream_connect_attempts_per_request{bucket="1"} 45640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22336
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 196
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1967
telemt_me_reconnect_success_total 898
telemt_me_reader_eof_total 870
telemt_me_idle_close_by_peer_total 870
telemt_me_route_drop_no_conn_total 2276148
telemt_me_route_drop_channel_closed_total 273
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4863861
telemt_me_endpoint_quarantine_total 705
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 866
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
telemt_me_writers_active_current 48
telemt_desync_total 22915
telemt_desync_full_logged_total 7810
telemt_desync_suppressed_total 15105
telemt_desync_frames_bucket_total{bucket="1_2"} 5508
telemt_desync_frames_bucket_total{bucket="3_10"} 8897
telemt_desync_frames_bucket_total{bucket="gt_10"} 8510
telemt_pool_swap_total 122
telemt_pool_force_close_total 3619
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 36679
telemt_me_writer_removed_unexpected_total 854
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3041
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34430
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3406
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33060
telemt_me_writer_teardown_success_total{mode="normal"} 37471
telemt_me_writer_teardown_noop_total 36685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74156
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.472277
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74156
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 785
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 4785906
telemt_user_connections_current{user="hello"} 2061
telemt_user_octets_from_client{user="hello"} 142143864405 (132.38 GB)
telemt_user_octets_to_client{user="hello"} 2266293511023 (2.06 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 993
telemt_user_unique_ips_recent_window{user="hello"} 242
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 112254.9 (31h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6393981
telemt_connections_bad_total 550709
telemt_connections_current 1702
telemt_connections_me_current 1702
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 208817
telemt_upstream_connect_attempt_total 51962
telemt_upstream_connect_success_total 51562
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 51699
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 557
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1095
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2181
telemt_me_reconnect_success_total 939
telemt_me_reader_eof_total 888
telemt_me_idle_close_by_peer_total 888
telemt_me_route_drop_no_conn_total 2174703
telemt_me_route_drop_channel_closed_total 126
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4749310
telemt_me_endpoint_quarantine_total 794
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 840
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
telemt_me_writers_active_current 44
telemt_desync_total 22784
telemt_desync_full_logged_total 7681
telemt_desync_suppressed_total 15103
telemt_desync_frames_bucket_total{bucket="1_2"} 5558
telemt_desync_frames_bucket_total{bucket="3_10"} 8731
telemt_desync_frames_bucket_total{bucket="gt_10"} 8495
telemt_pool_swap_total 121
telemt_pool_force_close_total 3507
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 395
telemt_me_draining_writers_reap_progress_total 37760
telemt_me_writer_removed_unexpected_total 857
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3135
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35499
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3292
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34253
telemt_me_writer_teardown_success_total{mode="normal"} 38634
telemt_me_writer_teardown_noop_total 37772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75608
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76406
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.169316
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76406
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 395
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 813
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 4744502
telemt_user_connections_current{user="hello"} 1702
telemt_user_octets_from_client{user="hello"} 134957271807 (125.69 GB)
telemt_user_octets_to_client{user="hello"} 2177361894163 (1.98 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 784
telemt_user_unique_ips_recent_window{user="hello"} 330
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 112294.1 (31h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20628671
telemt_connections_bad_total 1685745
telemt_connections_current 2652
telemt_connections_me_current 2652
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 620589
telemt_upstream_connect_attempt_total 202732
telemt_upstream_connect_success_total 184455
telemt_upstream_connect_fail_total 16465
telemt_upstream_connect_attempts_per_request{bucket="1"} 200920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 130101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44182
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1224
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8948
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16465
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65128
telemt_me_reconnect_success_total 2401
telemt_me_reader_eof_total 1487
telemt_me_idle_close_by_peer_total 1486
telemt_me_route_drop_no_conn_total 39546866
telemt_me_route_drop_channel_closed_total 127
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16628585
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 875
telemt_me_single_endpoint_outage_enter_total 143
telemt_me_single_endpoint_outage_exit_total 143
telemt_me_single_endpoint_outage_reconnect_attempt_total 296
telemt_me_single_endpoint_outage_reconnect_success_total 75
telemt_me_single_endpoint_quarantine_bypass_total 296
telemt_me_single_endpoint_shadow_rotate_total 880
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 67
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
telemt_desync_total 32231
telemt_desync_full_logged_total 9694
telemt_desync_suppressed_total 22537
telemt_desync_frames_bucket_total{bucket="1_2"} 6987
telemt_desync_frames_bucket_total{bucket="3_10"} 14299
telemt_desync_frames_bucket_total{bucket="gt_10"} 10945
telemt_pool_swap_total 116
telemt_pool_force_close_total 3741
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 827
telemt_me_draining_writers_reap_progress_total 35240
telemt_me_writer_removed_unexpected_total 2230
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4766
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32445
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3216
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 525
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31499
telemt_me_writer_teardown_success_total{mode="normal"} 37211
telemt_me_writer_teardown_noop_total 35267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68064
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72478
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 216.521564
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72478
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 827
telemt_me_refill_failed_total 3808
telemt_me_writer_restored_same_endpoint_total 1630
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 579
telemt_user_connections_total{user="hello"} 16763435
telemt_user_connections_current{user="hello"} 2652
telemt_user_octets_from_client{user="hello"} 231384727040 (215.49 GB)
telemt_user_octets_to_client{user="hello"} 1246584876515 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 398569
telemt_user_msgs_to_client{user="hello"} 788102
telemt_user_unique_ips_current{user="hello"} 1181
telemt_user_unique_ips_recent_window{user="hello"} 339
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 112261.6 (31h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6156189
telemt_connections_bad_total 596664
telemt_connections_current 2013
telemt_connections_me_current 2013
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 129435
telemt_upstream_connect_attempt_total 60688
telemt_upstream_connect_success_total 59994
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 60587
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_reconnect_attempts_total 69754
telemt_me_reconnect_success_total 1817
telemt_me_reader_eof_total 1600
telemt_me_idle_close_by_peer_total 1599
telemt_me_route_drop_no_conn_total 2406885
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4780464
telemt_me_endpoint_quarantine_total 762
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 852
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
telemt_me_writers_active_current 47
telemt_desync_total 23863
telemt_desync_full_logged_total 8379
telemt_desync_suppressed_total 15484
telemt_desync_frames_bucket_total{bucket="1_2"} 4607
telemt_desync_frames_bucket_total{bucket="3_10"} 9243
telemt_desync_frames_bucket_total{bucket="gt_10"} 10013
telemt_pool_swap_total 116
telemt_pool_force_close_total 3320
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 400
telemt_me_draining_writers_reap_progress_total 39731
telemt_me_writer_removed_unexpected_total 1637
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4038
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37362
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2919
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36411
telemt_me_writer_teardown_success_total{mode="normal"} 41400
telemt_me_writer_teardown_noop_total 39732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81132
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.226759
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81132
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 400
telemt_me_refill_failed_total 4210
telemt_me_writer_restored_same_endpoint_total 1525
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 4773153
telemt_user_connections_current{user="hello"} 2013
telemt_user_octets_from_client{user="hello"} 125987216784 (117.33 GB)
telemt_user_octets_to_client{user="hello"} 1955371735962 (1.78 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 938
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 49097.2 (13h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4086208
telemt_connections_bad_total 172938
telemt_connections_current 1600
telemt_connections_me_current 1600
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1644258
telemt_upstream_connect_attempt_total 29438
telemt_upstream_connect_success_total 29247
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 29431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_reconnect_attempts_total 45957
telemt_me_reconnect_success_total 994
telemt_me_reader_eof_total 680
telemt_me_idle_close_by_peer_total 680
telemt_me_route_drop_no_conn_total 1037343
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1998988
telemt_me_endpoint_quarantine_total 366
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 382
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10741
telemt_desync_full_logged_total 3714
telemt_desync_suppressed_total 7027
telemt_desync_frames_bucket_total{bucket="1_2"} 1975
telemt_desync_frames_bucket_total{bucket="3_10"} 4112
telemt_desync_frames_bucket_total{bucket="gt_10"} 4654
telemt_pool_swap_total 53
telemt_pool_force_close_total 1568
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 142
telemt_me_draining_writers_reap_progress_total 18313
telemt_me_writer_removed_unexpected_total 753
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1614
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17479
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1362
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16745
telemt_me_writer_teardown_success_total{mode="normal"} 19093
telemt_me_writer_teardown_noop_total 18315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37408
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.504579
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37408
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 142
telemt_me_refill_failed_total 2612
telemt_me_writer_restored_same_endpoint_total 888
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2002476
telemt_user_connections_current{user="hello"} 1600
telemt_user_octets_from_client{user="hello"} 55202839252 (51.41 GB)
telemt_user_octets_to_client{user="hello"} 849357555358 (791.03 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 796
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 30068.1 (8h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214858
telemt_connections_bad_total 1796
telemt_connections_current 356
telemt_connections_me_current 356
telemt_handshake_timeouts_total 5825
telemt_upstream_connect_attempt_total 14533
telemt_upstream_connect_success_total 14498
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 14531
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8282
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 333
telemt_me_reconnect_success_total 190
telemt_me_reader_eof_total 195
telemt_me_idle_close_by_peer_total 195
telemt_me_route_drop_no_conn_total 59514
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189864
telemt_me_endpoint_quarantine_total 292
telemt_me_single_endpoint_shadow_rotate_total 263
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
telemt_desync_total 1095
telemt_desync_full_logged_total 283
telemt_desync_suppressed_total 812
telemt_desync_frames_bucket_total{bucket="1_2"} 400
telemt_desync_frames_bucket_total{bucket="3_10"} 415
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 33
telemt_pool_force_close_total 737
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 13144
telemt_me_writer_removed_unexpected_total 188
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 840
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12499
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 735
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12407
telemt_me_writer_teardown_success_total{mode="normal"} 13339
telemt_me_writer_teardown_noop_total 13144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26483
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.068594
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26483
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 172
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 189532
telemt_user_connections_current{user="hello"} 356
telemt_user_octets_from_client{user="hello"} 3317631912 (3.09 GB)
telemt_user_octets_to_client{user="hello"} 116410198484 (108.42 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 112265.7 (31h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7472506
telemt_connections_bad_total 752447
telemt_connections_current 2051
telemt_connections_me_current 2051
telemt_handshake_timeouts_total 213184
telemt_upstream_connect_attempt_total 44199
telemt_upstream_connect_success_total 44039
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 44162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21799
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_reconnect_attempts_total 1637
telemt_me_reconnect_success_total 870
telemt_me_reader_eof_total 856
telemt_me_idle_close_by_peer_total 856
telemt_me_route_drop_no_conn_total 2146073
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5569722
telemt_me_endpoint_quarantine_total 795
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 865
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
telemt_me_writers_active_current 47
telemt_desync_total 21840
telemt_desync_full_logged_total 7167
telemt_desync_suppressed_total 14673
telemt_desync_frames_bucket_total{bucket="1_2"} 5487
telemt_desync_frames_bucket_total{bucket="3_10"} 7912
telemt_desync_frames_bucket_total{bucket="gt_10"} 8441
telemt_pool_swap_total 124
telemt_pool_force_close_total 3311
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 39883
telemt_me_writer_removed_unexpected_total 825
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3113
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37616
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3223
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36572
telemt_me_writer_teardown_success_total{mode="normal"} 40729
telemt_me_writer_teardown_noop_total 39885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80614
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.695831
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80614
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 778
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 5544615
telemt_user_connections_current{user="hello"} 2051
telemt_user_octets_from_client{user="hello"} 110683136460 (103.08 GB)
telemt_user_octets_to_client{user="hello"} 2584079352916 (2.35 TB)
telemt_user_unique_ips_current{user="hello"} 912
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 112262.4 (31h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6473903
telemt_connections_bad_total 636479
telemt_connections_current 1920
telemt_connections_me_current 1920
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 175126
telemt_upstream_connect_attempt_total 60011
telemt_upstream_connect_success_total 59563
telemt_upstream_connect_fail_total 389
telemt_upstream_connect_attempts_per_request{bucket="1"} 59952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34591
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23838
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 389
telemt_me_reconnect_attempts_total 5608
telemt_me_reconnect_success_total 1207
telemt_me_reader_eof_total 1090
telemt_me_idle_close_by_peer_total 1090
telemt_me_seq_mismatch_total 52
telemt_me_route_drop_no_conn_total 2198469
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4935936
telemt_me_endpoint_quarantine_total 888
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 859
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
telemt_me_writers_active_current 43
telemt_desync_total 20457
telemt_desync_full_logged_total 6826
telemt_desync_suppressed_total 13631
telemt_desync_frames_bucket_total{bucket="1_2"} 5223
telemt_desync_frames_bucket_total{bucket="3_10"} 7473
telemt_desync_frames_bucket_total{bucket="gt_10"} 7761
telemt_pool_swap_total 122
telemt_pool_force_close_total 3265
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 389
telemt_me_draining_writers_reap_progress_total 38459
telemt_me_writer_removed_unexpected_total 1102
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3649
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35967
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35194
telemt_me_writer_teardown_success_total{mode="normal"} 39616
telemt_me_writer_teardown_noop_total 38463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78079
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.165566
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78079
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 389
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 942
telemt_me_writer_restored_fallback_total 70
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4938827
telemt_user_connections_current{user="hello"} 1920
telemt_user_octets_from_client{user="hello"} 93131390993 (86.74 GB)
telemt_user_octets_to_client{user="hello"} 2113210562852 (1.92 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 877
telemt_user_unique_ips_recent_window{user="hello"} 220
```