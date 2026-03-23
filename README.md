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

# Server Metrics 2026-03-23 03:43:34 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 110230.3 (30h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3760323
telemt_connections_bad_total 365886
telemt_connections_current 1109
telemt_connections_me_current 1109
telemt_handshake_timeouts_total 123660
telemt_upstream_connect_attempt_total 41131
telemt_upstream_connect_success_total 41130
telemt_upstream_connect_attempts_per_request{bucket="1"} 41130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26667
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1438
telemt_me_reconnect_success_total 638
telemt_me_reader_eof_total 655
telemt_me_idle_close_by_peer_total 655
telemt_me_route_drop_no_conn_total 3019104
telemt_me_route_drop_channel_closed_total 1239
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3067283
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 785
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 862
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
telemt_desync_total 13124
telemt_desync_full_logged_total 4171
telemt_desync_suppressed_total 8953
telemt_desync_frames_bucket_total{bucket="1_2"} 3470
telemt_desync_frames_bucket_total{bucket="3_10"} 4804
telemt_desync_frames_bucket_total{bucket="gt_10"} 4850
telemt_pool_swap_total 122
telemt_pool_force_close_total 3715
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 678
telemt_me_draining_writers_reap_progress_total 37678
telemt_me_writer_removed_unexpected_total 632
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2690
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35268
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3659
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33963
telemt_me_writer_teardown_success_total{mode="normal"} 37958
telemt_me_writer_teardown_noop_total 37689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75647
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 380.515213
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75647
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 678
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 572
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 3056108
telemt_user_connections_current{user="hello"} 1109
telemt_user_octets_from_client{user="hello"} 43257188720 (40.29 GB)
telemt_user_octets_to_client{user="hello"} 831629468460 (774.52 GB)
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 123596.6 (34h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4065134
telemt_connections_bad_total 379030
telemt_connections_current 324
telemt_connections_me_current 324
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 102413
telemt_upstream_connect_attempt_total 77654
telemt_upstream_connect_success_total 76728
telemt_upstream_connect_fail_total 819
telemt_upstream_connect_attempts_per_request{bucket="1"} 77547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 42770
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33741
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 217
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 819
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10548
telemt_me_reconnect_success_total 3760
telemt_me_reader_eof_total 3743
telemt_me_idle_close_by_peer_total 3743
telemt_me_route_drop_no_conn_total 3650199
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3226147
telemt_me_endpoint_quarantine_total 1003
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 973
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 13171
telemt_desync_full_logged_total 7405
telemt_desync_suppressed_total 5766
telemt_desync_frames_bucket_total{bucket="1_2"} 2992
telemt_desync_frames_bucket_total{bucket="3_10"} 5167
telemt_desync_frames_bucket_total{bucket="gt_10"} 5012
telemt_pool_swap_total 117
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 257
telemt_me_draining_writers_reap_progress_total 51490
telemt_me_writer_removed_unexpected_total 3666
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6584
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48612
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2788
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48244
telemt_me_writer_teardown_success_total{mode="normal"} 55196
telemt_me_writer_teardown_noop_total 51491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106685
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106687
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.714417
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106687
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 257
telemt_me_refill_failed_total 266
telemt_me_writer_restored_same_endpoint_total 3332
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 303
telemt_user_connections_total{user="hello"} 3240625
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 43600598663 (40.61 GB)
telemt_user_octets_to_client{user="hello"} 806980804741 (751.56 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 112
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 198456.6 (55h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16477887
telemt_connections_bad_total 1670099
telemt_connections_current 1187
telemt_connections_me_current 1187
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 401033
telemt_upstream_connect_attempt_total 89446
telemt_upstream_connect_success_total 89339
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 89356
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44003
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1725
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3096
telemt_me_reconnect_success_total 1637
telemt_me_reader_eof_total 1591
telemt_me_idle_close_by_peer_total 1589
telemt_me_route_drop_no_conn_total 14069385
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13083538
telemt_me_endpoint_quarantine_total 1337
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1501
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_desync_total 54396
telemt_desync_full_logged_total 17341
telemt_desync_suppressed_total 37055
telemt_desync_frames_bucket_total{bucket="1_2"} 12121
telemt_desync_frames_bucket_total{bucket="3_10"} 21254
telemt_desync_frames_bucket_total{bucket="gt_10"} 21021
telemt_pool_swap_total 215
telemt_pool_force_close_total 6945
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1077
telemt_me_draining_writers_reap_progress_total 68506
telemt_me_writer_removed_unexpected_total 1527
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5762
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63554
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6475
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61561
telemt_me_writer_teardown_success_total{mode="normal"} 69316
telemt_me_writer_teardown_noop_total 68559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 130371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 134547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 137265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 137836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 137866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 137867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 137871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 137873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 137875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 137875
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.093543
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 137875
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1077
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1419
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 13083507
telemt_user_connections_current{user="hello"} 1187
telemt_user_octets_from_client{user="hello"} 198297378121 (184.68 GB)
telemt_user_octets_to_client{user="hello"} 3534324249959 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 543
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 198457.9 (55h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12021812
telemt_connections_bad_total 1266794
telemt_connections_current 789
telemt_connections_me_current 789
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 346536
telemt_upstream_connect_attempt_total 103717
telemt_upstream_connect_success_total 102375
telemt_upstream_connect_fail_total 889
telemt_upstream_connect_attempts_per_request{bucket="1"} 103264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43852
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3803
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 889
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4557
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 1822
telemt_me_idle_close_by_peer_total 1822
telemt_me_route_drop_no_conn_total 4573312
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8900496
telemt_me_endpoint_quarantine_total 1358
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1522
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 39148
telemt_desync_full_logged_total 13190
telemt_desync_suppressed_total 25958
telemt_desync_frames_bucket_total{bucket="1_2"} 9695
telemt_desync_frames_bucket_total{bucket="3_10"} 15041
telemt_desync_frames_bucket_total{bucket="gt_10"} 14412
telemt_pool_swap_total 212
telemt_pool_force_close_total 6289
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 716
telemt_me_draining_writers_reap_progress_total 66592
telemt_me_writer_removed_unexpected_total 1849
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5842
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62458
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5777
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60303
telemt_me_writer_teardown_success_total{mode="normal"} 68300
telemt_me_writer_teardown_noop_total 66617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 128148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 131393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 132542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 133733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 134492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 134832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 134907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 134909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 134915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 134917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 134917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 134917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 134917
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.571998
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 134917
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 716
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 1673
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 8838185
telemt_user_connections_current{user="hello"} 789
telemt_user_octets_from_client{user="hello"} 218575838496 (203.56 GB)
telemt_user_octets_to_client{user="hello"} 3990681790387 (3.63 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 353
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 198421.9 (55h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11166326
telemt_connections_bad_total 1003301
telemt_connections_current 691
telemt_connections_me_current 691
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 347506
telemt_upstream_connect_attempt_total 88186
telemt_upstream_connect_success_total 86618
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 86823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42436
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2050
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2368
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5833
telemt_me_reconnect_success_total 2440
telemt_me_reader_eof_total 2187
telemt_me_idle_close_by_peer_total 2186
telemt_me_route_drop_no_conn_total 5351530
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8422094
telemt_me_endpoint_quarantine_total 1395
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1477
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38377
telemt_desync_full_logged_total 12727
telemt_desync_suppressed_total 25650
telemt_desync_frames_bucket_total{bucket="1_2"} 9692
telemt_desync_frames_bucket_total{bucket="3_10"} 14702
telemt_desync_frames_bucket_total{bucket="gt_10"} 13983
telemt_pool_swap_total 208
telemt_pool_force_close_total 6189
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 752
telemt_me_draining_writers_reap_progress_total 67145
telemt_me_writer_removed_unexpected_total 2333
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6591
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62823
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5618
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 60956
telemt_me_writer_teardown_success_total{mode="normal"} 69414
telemt_me_writer_teardown_noop_total 67216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136630
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.897287
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136630
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 752
telemt_me_refill_failed_total 180
telemt_me_writer_restored_same_endpoint_total 2123
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 8413983
telemt_user_connections_current{user="hello"} 691
telemt_user_octets_from_client{user="hello"} 193260010019 (179.99 GB)
telemt_user_octets_to_client{user="hello"} 3493148157993 (3.18 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 68702.0 (19h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11423640
telemt_connections_bad_total 673728
telemt_connections_current 1333
telemt_connections_me_current 1333
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 293712
telemt_upstream_connect_attempt_total 63446
telemt_upstream_connect_success_total 60069
telemt_upstream_connect_fail_total 2199
telemt_upstream_connect_attempts_per_request{bucket="1"} 62268
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21525
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6033
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2199
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8146
telemt_me_reconnect_success_total 1414
telemt_me_reader_eof_total 903
telemt_me_idle_close_by_peer_total 902
telemt_me_route_drop_no_conn_total 25319321
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9468652
telemt_me_endpoint_quarantine_total 531
telemt_me_single_endpoint_outage_enter_total 102
telemt_me_single_endpoint_outage_exit_total 102
telemt_me_single_endpoint_outage_reconnect_attempt_total 200
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 200
telemt_me_single_endpoint_shadow_rotate_total 554
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
telemt_me_writers_active_current 42
telemt_desync_total 16809
telemt_desync_full_logged_total 4624
telemt_desync_suppressed_total 12185
telemt_desync_frames_bucket_total{bucket="1_2"} 3222
telemt_desync_frames_bucket_total{bucket="3_10"} 6857
telemt_desync_frames_bucket_total{bucket="gt_10"} 6730
telemt_pool_swap_total 71
telemt_pool_force_close_total 2236
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 506
telemt_me_draining_writers_reap_progress_total 22625
telemt_me_writer_removed_unexpected_total 1298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2945
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20928
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1914
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20389
telemt_me_writer_teardown_success_total{mode="normal"} 23873
telemt_me_writer_teardown_noop_total 22644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46517
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.134051
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46517
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 506
telemt_me_refill_failed_total 345
telemt_me_writer_restored_same_endpoint_total 912
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 9495136
telemt_user_connections_current{user="hello"} 1333
telemt_user_octets_from_client{user="hello"} 88758885406 (82.66 GB)
telemt_user_octets_to_client{user="hello"} 653563374625 (608.68 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 505
telemt_user_unique_ips_recent_window{user="hello"} 196
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 198428.5 (55h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11135317
telemt_connections_bad_total 982990
telemt_connections_current 929
telemt_connections_me_current 929
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 245013
telemt_upstream_connect_attempt_total 116984
telemt_upstream_connect_success_total 115787
telemt_upstream_connect_fail_total 1020
telemt_upstream_connect_attempts_per_request{bucket="1"} 116807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 68270
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1372
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1020
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73222
telemt_me_reconnect_success_total 3181
telemt_me_reader_eof_total 2879
telemt_me_idle_close_by_peer_total 2876
telemt_me_route_drop_no_conn_total 5284120
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8766478
telemt_me_endpoint_quarantine_total 1350
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1508
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 46708
telemt_desync_full_logged_total 16032
telemt_desync_suppressed_total 30676
telemt_desync_frames_bucket_total{bucket="1_2"} 9491
telemt_desync_frames_bucket_total{bucket="3_10"} 17897
telemt_desync_frames_bucket_total{bucket="gt_10"} 19320
telemt_pool_swap_total 204
telemt_pool_force_close_total 5911
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 71146
telemt_me_writer_removed_unexpected_total 2898
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7132
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66957
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5162
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 65235
telemt_me_writer_teardown_success_total{mode="normal"} 74089
telemt_me_writer_teardown_noop_total 71147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 144500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 144919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 145192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 145226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 145229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 145229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145236
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.329686
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145236
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 4310
telemt_me_writer_restored_same_endpoint_total 2682
telemt_me_writer_restored_fallback_total 53
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 8769314
telemt_user_connections_current{user="hello"} 929
telemt_user_octets_from_client{user="hello"} 196884288781 (183.36 GB)
telemt_user_octets_to_client{user="hello"} 3352073891368 (3.05 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 135264.8 (37h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11860967
telemt_connections_bad_total 486931
telemt_connections_current 792
telemt_connections_me_current 792
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4800617
telemt_upstream_connect_attempt_total 65796
telemt_upstream_connect_success_total 65323
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 65783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30525
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_reconnect_attempts_total 49221
telemt_me_reconnect_success_total 1923
telemt_me_reader_eof_total 1601
telemt_me_idle_close_by_peer_total 1600
telemt_me_route_drop_no_conn_total 4110798
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5697364
telemt_me_endpoint_quarantine_total 932
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1044
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31980
telemt_desync_full_logged_total 10939
telemt_desync_suppressed_total 21041
telemt_desync_frames_bucket_total{bucket="1_2"} 6387
telemt_desync_frames_bucket_total{bucket="3_10"} 12613
telemt_desync_frames_bucket_total{bucket="gt_10"} 12980
telemt_pool_swap_total 144
telemt_pool_force_close_total 4109
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 50886
telemt_me_writer_removed_unexpected_total 1644
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4081
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48500
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3665
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46777
telemt_me_writer_teardown_success_total{mode="normal"} 52581
telemt_me_writer_teardown_noop_total 50893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103474
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.762297
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103474
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 2748
telemt_me_writer_restored_same_endpoint_total 1699
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5689402
telemt_user_connections_current{user="hello"} 792
telemt_user_octets_from_client{user="hello"} 120671355516 (112.38 GB)
telemt_user_octets_to_client{user="hello"} 2214348292202 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 344
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 116235.6 (32h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1597241
telemt_connections_bad_total 37028
telemt_connections_current 622
telemt_connections_me_current 622
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 32786
telemt_upstream_connect_attempt_total 55035
telemt_upstream_connect_success_total 54863
telemt_upstream_connect_fail_total 144
telemt_upstream_connect_attempts_per_request{bucket="1"} 55007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25792
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 811
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 144
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2406
telemt_me_reconnect_success_total 970
telemt_me_reader_eof_total 964
telemt_me_idle_close_by_peer_total 964
telemt_me_route_drop_no_conn_total 534925
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1419225
telemt_me_endpoint_quarantine_total 988
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 960
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 9974
telemt_desync_full_logged_total 2814
telemt_desync_suppressed_total 7160
telemt_desync_frames_bucket_total{bucket="1_2"} 3130
telemt_desync_frames_bucket_total{bucket="3_10"} 3766
telemt_desync_frames_bucket_total{bucket="gt_10"} 3078
telemt_pool_swap_total 126
telemt_pool_force_close_total 3148
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 46822
telemt_me_writer_removed_unexpected_total 928
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3536
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44257
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3060
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43674
telemt_me_writer_teardown_success_total{mode="normal"} 47793
telemt_me_writer_teardown_noop_total 46826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94619
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94619
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.510002
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94619
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 828
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 1414924
telemt_user_connections_current{user="hello"} 622
telemt_user_octets_from_client{user="hello"} 26717468749 (24.88 GB)
telemt_user_octets_to_client{user="hello"} 594494179347 (553.67 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 198433.1 (55h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13435359
telemt_connections_bad_total 1627613
telemt_connections_current 1003
telemt_connections_me_current 1003
telemt_handshake_timeouts_total 392097
telemt_upstream_connect_attempt_total 79692
telemt_upstream_connect_success_total 79335
telemt_upstream_connect_fail_total 221
telemt_upstream_connect_attempts_per_request{bucket="1"} 79556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39211
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40020
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 221
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3096
telemt_me_reconnect_success_total 1570
telemt_me_reader_eof_total 1557
telemt_me_idle_close_by_peer_total 1557
telemt_me_route_drop_no_conn_total 4497696
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10120318
telemt_me_endpoint_quarantine_total 1457
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1505
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 42494
telemt_desync_full_logged_total 13878
telemt_desync_suppressed_total 28616
telemt_desync_frames_bucket_total{bucket="1_2"} 10349
telemt_desync_frames_bucket_total{bucket="3_10"} 15611
telemt_desync_frames_bucket_total{bucket="gt_10"} 16534
telemt_pool_swap_total 220
telemt_pool_force_close_total 5767
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 72143
telemt_me_writer_removed_unexpected_total 1491
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5578
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68112
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5593
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66376
telemt_me_writer_teardown_success_total{mode="normal"} 73690
telemt_me_writer_teardown_noop_total 72145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 143214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 144943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 145326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 145702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 145822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 145835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 145835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 145835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 145835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 145835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 145835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 145835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 145835
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.886087
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 145835
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 82
telemt_me_writer_restored_same_endpoint_total 1383
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 10086930
telemt_user_connections_current{user="hello"} 1003
telemt_user_octets_from_client{user="hello"} 195514851628 (182.09 GB)
telemt_user_octets_to_client{user="hello"} 4487311782684 (4.08 TB)
telemt_user_unique_ips_current{user="hello"} 421
telemt_user_unique_ips_recent_window{user="hello"} 113
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 198429.7 (55h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11750839
telemt_connections_bad_total 1378553
telemt_connections_current 752
telemt_connections_me_current 752
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 315090
telemt_upstream_connect_attempt_total 107379
telemt_upstream_connect_success_total 106452
telemt_upstream_connect_fail_total 719
telemt_upstream_connect_attempts_per_request{bucket="1"} 107171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 57831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45638
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2070
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 719
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10861
telemt_me_reconnect_success_total 2686
telemt_me_reader_eof_total 2493
telemt_me_idle_close_by_peer_total 2492
telemt_me_seq_mismatch_total 104
telemt_me_route_drop_no_conn_total 5665984
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9038510
telemt_me_endpoint_quarantine_total 1630
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1511
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42136
telemt_desync_full_logged_total 13569
telemt_desync_suppressed_total 28567
telemt_desync_frames_bucket_total{bucket="1_2"} 10949
telemt_desync_frames_bucket_total{bucket="3_10"} 15483
telemt_desync_frames_bucket_total{bucket="gt_10"} 15704
telemt_pool_swap_total 210
telemt_pool_force_close_total 5531
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 676
telemt_me_draining_writers_reap_progress_total 72345
telemt_me_writer_removed_unexpected_total 2529
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6953
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68018
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5060
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66814
telemt_me_writer_teardown_success_total{mode="normal"} 74971
telemt_me_writer_teardown_noop_total 72350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 144615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 146413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 146952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 147271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 147321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 147321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 147321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 147321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 147321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 147321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 147321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 147321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 147321
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.595224
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 147321
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 676
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 2146
telemt_me_writer_restored_fallback_total 140
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 9043055
telemt_user_connections_current{user="hello"} 752
telemt_user_octets_from_client{user="hello"} 158086451632 (147.23 GB)
telemt_user_octets_to_client{user="hello"} 3528154140762 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 86
```