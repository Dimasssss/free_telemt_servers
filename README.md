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

# Server Metrics 2026-03-22 15:02:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 64591.6 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2206907
telemt_connections_bad_total 112142
telemt_connections_current 2002
telemt_connections_me_current 2002
telemt_handshake_timeouts_total 84770
telemt_upstream_connect_attempt_total 23987
telemt_upstream_connect_success_total 23986
telemt_upstream_connect_attempts_per_request{bucket="1"} 23986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15576
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 979
telemt_me_reconnect_success_total 403
telemt_me_reader_eof_total 405
telemt_me_idle_close_by_peer_total 405
telemt_me_route_drop_no_conn_total 1742311
telemt_me_route_drop_channel_closed_total 707
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1875537
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 508
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 9417
telemt_desync_full_logged_total 2909
telemt_desync_suppressed_total 6508
telemt_desync_frames_bucket_total{bucket="1_2"} 2586
telemt_desync_frames_bucket_total{bucket="3_10"} 3530
telemt_desync_frames_bucket_total{bucket="gt_10"} 3301
telemt_pool_swap_total 71
telemt_pool_force_close_total 2167
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 21893
telemt_me_writer_removed_unexpected_total 392
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1577
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20529
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2122
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19726
telemt_me_writer_teardown_success_total{mode="normal"} 22106
telemt_me_writer_teardown_noop_total 21897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44003
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 186.857192
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44003
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 354
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 1872418
telemt_user_connections_current{user="hello"} 2002
telemt_user_octets_from_client{user="hello"} 28758863692 (26.78 GB)
telemt_user_octets_to_client{user="hello"} 511876365624 (476.72 GB)
telemt_user_unique_ips_current{user="hello"} 704
telemt_user_unique_ips_recent_window{user="hello"} 311
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 77957.7 (21h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3477487
telemt_connections_bad_total 313645
telemt_connections_current 2547
telemt_connections_me_current 2547
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 81514
telemt_upstream_connect_attempt_total 49507
telemt_upstream_connect_success_total 48909
telemt_upstream_connect_fail_total 529
telemt_upstream_connect_attempts_per_request{bucket="1"} 49438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28904
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19847
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 529
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5633
telemt_me_reconnect_success_total 1941
telemt_me_reader_eof_total 1865
telemt_me_idle_close_by_peer_total 1865
telemt_me_route_drop_no_conn_total 3479065
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2758485
telemt_me_endpoint_quarantine_total 630
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 605
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
telemt_me_writers_active_current 87
telemt_desync_total 10613
telemt_desync_full_logged_total 5878
telemt_desync_suppressed_total 4735
telemt_desync_frames_bucket_total{bucket="1_2"} 2497
telemt_desync_frames_bucket_total{bucket="3_10"} 4193
telemt_desync_frames_bucket_total{bucket="gt_10"} 3923
telemt_pool_swap_total 74
telemt_pool_force_close_total 2174
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 185
telemt_me_draining_writers_reap_progress_total 30845
telemt_me_writer_removed_unexpected_total 1823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3586
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29083
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1882
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 292
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28671
telemt_me_writer_teardown_success_total{mode="normal"} 32669
telemt_me_writer_teardown_noop_total 30845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63514
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.529916
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63514
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 185
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1652
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 147
telemt_user_connections_total{user="hello"} 2769904
telemt_user_connections_current{user="hello"} 2547
telemt_user_octets_from_client{user="hello"} 33577567227 (31.27 GB)
telemt_user_octets_to_client{user="hello"} 597609157034 (556.57 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1540
telemt_user_unique_ips_recent_window{user="hello"} 811
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 152817.5 (42h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14995566
telemt_connections_bad_total 1359697
telemt_connections_current 5697
telemt_connections_me_current 5697
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 364881
telemt_upstream_connect_attempt_total 69493
telemt_upstream_connect_success_total 69399
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 69416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32636
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1656
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2540
telemt_me_reconnect_success_total 1323
telemt_me_reader_eof_total 1261
telemt_me_idle_close_by_peer_total 1260
telemt_me_route_drop_no_conn_total 13580505
telemt_me_route_drop_channel_closed_total 133
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12010958
telemt_me_endpoint_quarantine_total 966
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1136
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 48413
telemt_desync_full_logged_total 15228
telemt_desync_suppressed_total 33185
telemt_desync_frames_bucket_total{bucket="1_2"} 10929
telemt_desync_frames_bucket_total{bucket="3_10"} 18957
telemt_desync_frames_bucket_total{bucket="gt_10"} 18527
telemt_pool_swap_total 164
telemt_pool_force_close_total 5596
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 913
telemt_me_draining_writers_reap_progress_total 50268
telemt_me_writer_removed_unexpected_total 1216
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4376
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46413
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5145
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 451
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44672
telemt_me_writer_teardown_success_total{mode="normal"} 50789
telemt_me_writer_teardown_noop_total 50318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96018
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101107
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 288.779370
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101107
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 913
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1136
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 12012536
telemt_user_connections_current{user="hello"} 5697
telemt_user_octets_from_client{user="hello"} 167430784497 (155.93 GB)
telemt_user_octets_to_client{user="hello"} 3083315072267 (2.80 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 2106
telemt_user_unique_ips_recent_window{user="hello"} 1116
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 152818.9 (42h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10840709
telemt_connections_bad_total 1044415
telemt_connections_current 5357
telemt_connections_me_current 5357
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 320575
telemt_upstream_connect_attempt_total 81662
telemt_upstream_connect_success_total 80512
telemt_upstream_connect_fail_total 826
telemt_upstream_connect_attempts_per_request{bucket="1"} 81338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32519
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3687
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 826
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3831
telemt_me_reconnect_success_total 1542
telemt_me_reader_eof_total 1416
telemt_me_idle_close_by_peer_total 1416
telemt_me_route_drop_no_conn_total 4298791
telemt_me_route_drop_channel_closed_total 475
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8091509
telemt_me_endpoint_quarantine_total 955
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1157
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
telemt_me_writers_active_current 89
telemt_desync_total 35965
telemt_desync_full_logged_total 12081
telemt_desync_suppressed_total 23884
telemt_desync_frames_bucket_total{bucket="1_2"} 8839
telemt_desync_frames_bucket_total{bucket="3_10"} 13840
telemt_desync_frames_bucket_total{bucket="gt_10"} 13286
telemt_pool_swap_total 162
telemt_pool_force_close_total 5012
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 637
telemt_me_draining_writers_reap_progress_total 48520
telemt_me_writer_removed_unexpected_total 1448
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4458
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45367
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4575
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 437
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43508
telemt_me_writer_teardown_success_total{mode="normal"} 49825
telemt_me_writer_teardown_noop_total 48535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98360
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 96.734837
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98360
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 637
telemt_me_refill_failed_total 124
telemt_me_writer_restored_same_endpoint_total 1313
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 8030546
telemt_user_connections_current{user="hello"} 5357
telemt_user_octets_from_client{user="hello"} 202085778821 (188.21 GB)
telemt_user_octets_to_client{user="hello"} 3616119299454 (3.29 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2206
telemt_user_unique_ips_recent_window{user="hello"} 658
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 152784.4 (42h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10284119
telemt_connections_bad_total 879568
telemt_connections_current 3960
telemt_connections_me_current 3960
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 328249
telemt_upstream_connect_attempt_total 66975
telemt_upstream_connect_success_total 66051
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 66233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31671
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31124
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1215
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2041
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4545
telemt_me_reconnect_success_total 1850
telemt_me_reader_eof_total 1604
telemt_me_idle_close_by_peer_total 1603
telemt_me_route_drop_no_conn_total 5075113
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7763885
telemt_me_endpoint_quarantine_total 1051
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1120
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
telemt_desync_total 35583
telemt_desync_full_logged_total 11791
telemt_desync_suppressed_total 23792
telemt_desync_frames_bucket_total{bucket="1_2"} 9014
telemt_desync_frames_bucket_total{bucket="3_10"} 13609
telemt_desync_frames_bucket_total{bucket="gt_10"} 12960
telemt_pool_swap_total 159
telemt_pool_force_close_total 4990
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 49088
telemt_me_writer_removed_unexpected_total 1747
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4917
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45827
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4457
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 533
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44098
telemt_me_writer_teardown_success_total{mode="normal"} 50744
telemt_me_writer_teardown_noop_total 49159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99816
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99903
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3168.604121
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99903
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1607
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 7757189
telemt_user_connections_current{user="hello"} 3960
telemt_user_octets_from_client{user="hello"} 179607737209 (167.27 GB)
telemt_user_octets_to_client{user="hello"} 3218810682073 (2.93 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1608
telemt_user_unique_ips_recent_window{user="hello"} 626
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 23062.8 (6h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9763774
telemt_connections_bad_total 603583
telemt_connections_current 7571
telemt_connections_me_current 7571
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 156633
telemt_upstream_connect_attempt_total 29686
telemt_upstream_connect_success_total 28214
telemt_upstream_connect_fail_total 1034
telemt_upstream_connect_attempts_per_request{bucket="1"} 29248
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4765
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1034
telemt_me_keepalive_timeout_total 925
telemt_me_reconnect_attempts_total 5529
telemt_me_reconnect_success_total 606
telemt_me_reader_eof_total 399
telemt_me_idle_close_by_peer_total 399
telemt_me_route_drop_no_conn_total 24202722
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8140606
telemt_me_endpoint_quarantine_total 143
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 63
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 63
telemt_me_single_endpoint_shadow_rotate_total 175
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 12333
telemt_desync_full_logged_total 3148
telemt_desync_suppressed_total 9185
telemt_desync_frames_bucket_total{bucket="1_2"} 2138
telemt_desync_frames_bucket_total{bucket="3_10"} 5037
telemt_desync_frames_bucket_total{bucket="gt_10"} 5158
telemt_pool_swap_total 21
telemt_pool_force_close_total 888
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 320
telemt_me_draining_writers_reap_progress_total 6100
telemt_me_writer_removed_unexpected_total 518
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1035
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5546
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 620
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 268
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5212
telemt_me_writer_teardown_success_total{mode="normal"} 6581
telemt_me_writer_teardown_noop_total 6105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 12585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 12678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 12686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 12686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 12686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 12686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 12686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 12686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 12686
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.898402
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 12686
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 320
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 434
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 8155114
telemt_user_connections_current{user="hello"} 7571
telemt_user_octets_from_client{user="hello"} 47814191175 (44.53 GB)
telemt_user_octets_to_client{user="hello"} 236813761844 (220.55 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2608
telemt_user_unique_ips_recent_window{user="hello"} 1548
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 152789.8 (42h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10011082
telemt_connections_bad_total 831594
telemt_connections_current 5012
telemt_connections_me_current 5012
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 219606
telemt_upstream_connect_attempt_total 91458
telemt_upstream_connect_success_total 90530
telemt_upstream_connect_fail_total 803
telemt_upstream_connect_attempts_per_request{bucket="1"} 91333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1261
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 803
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71521
telemt_me_reconnect_success_total 2498
telemt_me_reader_eof_total 2225
telemt_me_idle_close_by_peer_total 2224
telemt_me_route_drop_no_conn_total 4978546
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7906471
telemt_me_endpoint_quarantine_total 1024
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1137
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 40716
telemt_desync_full_logged_total 13958
telemt_desync_suppressed_total 26758
telemt_desync_frames_bucket_total{bucket="1_2"} 8270
telemt_desync_frames_bucket_total{bucket="3_10"} 15792
telemt_desync_frames_bucket_total{bucket="gt_10"} 16654
telemt_pool_swap_total 156
telemt_pool_force_close_total 4652
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 570
telemt_me_draining_writers_reap_progress_total 51875
telemt_me_writer_removed_unexpected_total 2251
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5502
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48642
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 655
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47223
telemt_me_writer_teardown_success_total{mode="normal"} 54144
telemt_me_writer_teardown_noop_total 51876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106020
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.162468
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106020
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 570
telemt_me_refill_failed_total 4258
telemt_me_writer_restored_same_endpoint_total 2096
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 7906920
telemt_user_connections_current{user="hello"} 5012
telemt_user_octets_from_client{user="hello"} 179967165843 (167.61 GB)
telemt_user_octets_to_client{user="hello"} 2971827309449 (2.70 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 2006
telemt_user_unique_ips_recent_window{user="hello"} 757
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 89625.8 (24h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10339306
telemt_connections_bad_total 378207
telemt_connections_current 5284
telemt_connections_me_current 5284
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4356053
telemt_upstream_connect_attempt_total 43518
telemt_upstream_connect_success_total 43201
telemt_upstream_connect_fail_total 308
telemt_upstream_connect_attempts_per_request{bucket="1"} 43509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 308
telemt_me_reconnect_attempts_total 47960
telemt_me_reconnect_success_total 1475
telemt_me_reader_eof_total 1140
telemt_me_idle_close_by_peer_total 1139
telemt_me_route_drop_no_conn_total 3848865
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4967347
telemt_me_endpoint_quarantine_total 584
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 674
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_desync_total 27148
telemt_desync_full_logged_total 9148
telemt_desync_suppressed_total 18000
telemt_desync_frames_bucket_total{bucket="1_2"} 5495
telemt_desync_frames_bucket_total{bucket="3_10"} 10722
telemt_desync_frames_bucket_total{bucket="gt_10"} 10931
telemt_pool_swap_total 94
telemt_pool_force_close_total 2923
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 303
telemt_me_draining_writers_reap_progress_total 30746
telemt_me_writer_removed_unexpected_total 1204
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2790
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29189
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 418
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27823
telemt_me_writer_teardown_success_total{mode="normal"} 31979
telemt_me_writer_teardown_noop_total 30753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62732
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.549484
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62732
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 303
telemt_me_refill_failed_total 2702
telemt_me_writer_restored_same_endpoint_total 1315
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4961190
telemt_user_connections_current{user="hello"} 5284
telemt_user_octets_from_client{user="hello"} 106972851276 (99.63 GB)
telemt_user_octets_to_client{user="hello"} 1862113490630 (1.69 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1970
telemt_user_unique_ips_recent_window{user="hello"} 749
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 70596.5 (19h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 890914
telemt_connections_bad_total 11369
telemt_connections_current 1299
telemt_connections_me_current 1299
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 17718
telemt_upstream_connect_attempt_total 35210
telemt_upstream_connect_success_total 35122
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 35194
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16016
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18633
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 473
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1589
telemt_me_reconnect_success_total 673
telemt_me_reader_eof_total 648
telemt_me_idle_close_by_peer_total 648
telemt_me_route_drop_no_conn_total 304821
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 791479
telemt_me_endpoint_quarantine_total 624
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 588
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 4386
telemt_desync_full_logged_total 1332
telemt_desync_suppressed_total 3054
telemt_desync_frames_bucket_total{bucket="1_2"} 1041
telemt_desync_frames_bucket_total{bucket="3_10"} 1738
telemt_desync_frames_bucket_total{bucket="gt_10"} 1607
telemt_pool_swap_total 75
telemt_pool_force_close_total 1881
telemt_me_writer_close_signal_drop_total 108
telemt_me_draining_writers_reap_progress_total 29043
telemt_me_writer_removed_unexpected_total 627
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2232
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27461
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1803
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27162
telemt_me_writer_teardown_success_total{mode="normal"} 29693
telemt_me_writer_teardown_noop_total 29045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58713
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58738
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.329913
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58738
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 108
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 575
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 41
telemt_user_connections_total{user="hello"} 792583
telemt_user_connections_current{user="hello"} 1299
telemt_user_octets_from_client{user="hello"} 14712577233 (13.70 GB)
telemt_user_octets_to_client{user="hello"} 366530674215 (341.36 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 152794.1 (42h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12266501
telemt_connections_bad_total 1427934
telemt_connections_current 6995
telemt_connections_me_current 6995
telemt_handshake_timeouts_total 335989
telemt_upstream_connect_attempt_total 57183
telemt_upstream_connect_success_total 56960
telemt_upstream_connect_fail_total 173
telemt_upstream_connect_attempts_per_request{bucket="1"} 57133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28078
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28823
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 173
telemt_me_reconnect_attempts_total 2233
telemt_me_reconnect_success_total 1193
telemt_me_reader_eof_total 1157
telemt_me_idle_close_by_peer_total 1157
telemt_me_route_drop_no_conn_total 4031595
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9258835
telemt_me_endpoint_quarantine_total 1036
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1141
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 38036
telemt_desync_full_logged_total 12434
telemt_desync_suppressed_total 25602
telemt_desync_frames_bucket_total{bucket="1_2"} 9065
telemt_desync_frames_bucket_total{bucket="3_10"} 14092
telemt_desync_frames_bucket_total{bucket="gt_10"} 14879
telemt_pool_swap_total 169
telemt_pool_force_close_total 4678
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 601
telemt_me_draining_writers_reap_progress_total 51501
telemt_me_writer_removed_unexpected_total 1112
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4233
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48411
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4505
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46823
telemt_me_writer_teardown_success_total{mode="normal"} 52644
telemt_me_writer_teardown_noop_total 51503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104147
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.572236
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104147
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 601
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 1047
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 9228381
telemt_user_connections_current{user="hello"} 6995
telemt_user_octets_from_client{user="hello"} 177787770624 (165.58 GB)
telemt_user_octets_to_client{user="hello"} 4088157708676 (3.72 TB)
telemt_user_unique_ips_current{user="hello"} 2369
telemt_user_unique_ips_recent_window{user="hello"} 1168
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 152791.1 (42h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10639681
telemt_connections_bad_total 1188078
telemt_connections_current 5732
telemt_connections_me_current 5732
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 274239
telemt_upstream_connect_attempt_total 82889
telemt_upstream_connect_success_total 82270
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 82806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33948
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2019
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_reconnect_attempts_total 8798
telemt_me_reconnect_success_total 2017
telemt_me_reader_eof_total 1883
telemt_me_idle_close_by_peer_total 1883
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 5317862
telemt_me_route_drop_channel_closed_total 339
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8218849
telemt_me_endpoint_quarantine_total 1155
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1145
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_active_current 88
telemt_desync_total 37644
telemt_desync_full_logged_total 12158
telemt_desync_suppressed_total 25486
telemt_desync_frames_bucket_total{bucket="1_2"} 9371
telemt_desync_frames_bucket_total{bucket="3_10"} 14045
telemt_desync_frames_bucket_total{bucket="gt_10"} 14228
telemt_pool_swap_total 161
telemt_pool_force_close_total 4504
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 589
telemt_me_draining_writers_reap_progress_total 50857
telemt_me_writer_removed_unexpected_total 1908
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5306
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47526
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4092
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46353
telemt_me_writer_teardown_success_total{mode="normal"} 52832
telemt_me_writer_teardown_noop_total 50862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 103694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103694
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.837145
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103694
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 589
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 1640
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8225103
telemt_user_connections_current{user="hello"} 5732
telemt_user_octets_from_client{user="hello"} 144578365021 (134.65 GB)
telemt_user_octets_to_client{user="hello"} 3138813061103 (2.85 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2256
telemt_user_unique_ips_recent_window{user="hello"} 1034
```