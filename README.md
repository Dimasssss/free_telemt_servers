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

# Server Metrics 2026-03-23 01:00:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 100463.1 (27h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3504119
telemt_connections_bad_total 307641
telemt_connections_current 897
telemt_connections_me_current 897
telemt_handshake_timeouts_total 109249
telemt_upstream_connect_attempt_total 37287
telemt_upstream_connect_success_total 37286
telemt_upstream_connect_attempts_per_request{bucket="1"} 37286
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12958
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24196
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 92
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1394
telemt_me_reconnect_success_total 600
telemt_me_reader_eof_total 616
telemt_me_idle_close_by_peer_total 616
telemt_me_route_drop_no_conn_total 2982171
telemt_me_route_drop_channel_closed_total 1232
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2895130
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 705
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 784
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 12412
telemt_desync_full_logged_total 3893
telemt_desync_suppressed_total 8519
telemt_desync_frames_bucket_total{bucket="1_2"} 3352
telemt_desync_frames_bucket_total{bucket="3_10"} 4513
telemt_desync_frames_bucket_total{bucket="gt_10"} 4547
telemt_pool_swap_total 111
telemt_pool_force_close_total 3430
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 654
telemt_me_draining_writers_reap_progress_total 34129
telemt_me_writer_removed_unexpected_total 594
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2467
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31904
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3374
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30699
telemt_me_writer_teardown_success_total{mode="normal"} 34371
telemt_me_writer_teardown_noop_total 34140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68511
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 376.259562
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68511
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 654
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 537
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2884233
telemt_user_connections_current{user="hello"} 897
telemt_user_octets_from_client{user="hello"} 41169542292 (38.34 GB)
telemt_user_octets_to_client{user="hello"} 789195222284 (735.00 GB)
telemt_user_unique_ips_current{user="hello"} 429
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 113829.0 (31h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3997189
telemt_connections_bad_total 367197
telemt_connections_current 136
telemt_connections_me_current 136
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 100667
telemt_upstream_connect_attempt_total 71158
telemt_upstream_connect_success_total 70314
telemt_upstream_connect_fail_total 751
telemt_upstream_connect_attempts_per_request{bucket="1"} 71065
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30790
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 210
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 751
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9998
telemt_me_reconnect_success_total 3603
telemt_me_reader_eof_total 3598
telemt_me_idle_close_by_peer_total 3598
telemt_me_route_drop_no_conn_total 3640678
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3176530
telemt_me_endpoint_quarantine_total 902
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 44
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 44
telemt_me_single_endpoint_shadow_rotate_total 888
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 44
telemt_desync_total 12950
telemt_desync_full_logged_total 7260
telemt_desync_suppressed_total 5690
telemt_desync_frames_bucket_total{bucket="1_2"} 2939
telemt_desync_frames_bucket_total{bucket="3_10"} 5076
telemt_desync_frames_bucket_total{bucket="gt_10"} 4935
telemt_pool_swap_total 106
telemt_pool_force_close_total 3052
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 252
telemt_me_draining_writers_reap_progress_total 46788
telemt_me_writer_removed_unexpected_total 3530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6181
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44168
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43736
telemt_me_writer_teardown_success_total{mode="normal"} 50349
telemt_me_writer_teardown_noop_total 46789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 97123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97138
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.610164
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97138
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 252
telemt_me_refill_failed_total 246
telemt_me_writer_restored_same_endpoint_total 3221
telemt_me_writer_restored_fallback_total 29
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 3189833
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 43058190263 (40.10 GB)
telemt_user_octets_to_client{user="hello"} 791047693468 (736.72 GB)
telemt_user_msgs_from_client{user="hello"} 49657
telemt_user_msgs_to_client{user="hello"} 185005
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 188688.8 (52h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16324459
telemt_connections_bad_total 1644329
telemt_connections_current 783
telemt_connections_me_current 783
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 397303
telemt_upstream_connect_attempt_total 84483
telemt_upstream_connect_success_total 84378
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 84395
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1717
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2994
telemt_me_reconnect_success_total 1571
telemt_me_reader_eof_total 1519
telemt_me_idle_close_by_peer_total 1517
telemt_me_route_drop_no_conn_total 14044576
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12968497
telemt_me_endpoint_quarantine_total 1244
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1419
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 53772
telemt_desync_full_logged_total 17073
telemt_desync_suppressed_total 36699
telemt_desync_frames_bucket_total{bucket="1_2"} 11981
telemt_desync_frames_bucket_total{bucket="3_10"} 20979
telemt_desync_frames_bucket_total{bucket="gt_10"} 20812
telemt_pool_swap_total 204
telemt_pool_force_close_total 6701
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1060
telemt_me_draining_writers_reap_progress_total 63937
telemt_me_writer_removed_unexpected_total 1462
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5470
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59205
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6231
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57236
telemt_me_writer_teardown_success_total{mode="normal"} 64675
telemt_me_writer_teardown_noop_total 63990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 117530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 125337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128656
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128665
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.695269
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128665
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1060
telemt_me_refill_failed_total 78
telemt_me_writer_restored_same_endpoint_total 1359
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 12968531
telemt_user_connections_current{user="hello"} 783
telemt_user_octets_from_client{user="hello"} 191092743329 (177.97 GB)
telemt_user_octets_to_client{user="hello"} 3488123259359 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 404
telemt_user_unique_ips_recent_window{user="hello"} 93
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 188690.2 (52h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11873040
telemt_connections_bad_total 1233751
telemt_connections_current 628
telemt_connections_me_current 628
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344554
telemt_upstream_connect_attempt_total 98872
telemt_upstream_connect_success_total 97547
telemt_upstream_connect_fail_total 871
telemt_upstream_connect_attempts_per_request{bucket="1"} 98418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41153
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3801
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 871
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4432
telemt_me_reconnect_success_total 1882
telemt_me_reader_eof_total 1749
telemt_me_idle_close_by_peer_total 1749
telemt_me_route_drop_no_conn_total 4554829
telemt_me_route_drop_channel_closed_total 498
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8814026
telemt_me_endpoint_quarantine_total 1255
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1440
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_desync_total 38770
telemt_desync_full_logged_total 13058
telemt_desync_suppressed_total 25712
telemt_desync_frames_bucket_total{bucket="1_2"} 9604
telemt_desync_frames_bucket_total{bucket="3_10"} 14892
telemt_desync_frames_bucket_total{bucket="gt_10"} 14274
telemt_pool_swap_total 201
telemt_pool_force_close_total 6059
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 709
telemt_me_draining_writers_reap_progress_total 62161
telemt_me_writer_removed_unexpected_total 1779
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5562
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58234
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5547
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56102
telemt_me_writer_teardown_success_total{mode="normal"} 63796
telemt_me_writer_teardown_noop_total 62186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123607
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 125557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 125897
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 125972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 125974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 125980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 125982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 125982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 125982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 125982
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.420095
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 125982
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 709
telemt_me_refill_failed_total 137
telemt_me_writer_restored_same_endpoint_total 1610
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 8751788
telemt_user_connections_current{user="hello"} 628
telemt_user_octets_from_client{user="hello"} 217762700624 (202.81 GB)
telemt_user_octets_to_client{user="hello"} 3961687658527 (3.60 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 188654.2 (52h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11051573
telemt_connections_bad_total 974178
telemt_connections_current 463
telemt_connections_me_current 463
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345565
telemt_upstream_connect_attempt_total 83138
telemt_upstream_connect_success_total 81579
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 81784
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2027
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5743
telemt_me_reconnect_success_total 2367
telemt_me_reader_eof_total 2112
telemt_me_idle_close_by_peer_total 2111
telemt_me_route_drop_no_conn_total 5336671
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8353990
telemt_me_endpoint_quarantine_total 1324
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1396
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 69
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
telemt_desync_total 38125
telemt_desync_full_logged_total 12630
telemt_desync_suppressed_total 25495
telemt_desync_frames_bucket_total{bucket="1_2"} 9625
telemt_desync_frames_bucket_total{bucket="3_10"} 14588
telemt_desync_frames_bucket_total{bucket="gt_10"} 13912
telemt_pool_swap_total 197
telemt_pool_force_close_total 5961
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 739
telemt_me_draining_writers_reap_progress_total 62535
telemt_me_writer_removed_unexpected_total 2262
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6308
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58421
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5390
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 56574
telemt_me_writer_teardown_success_total{mode="normal"} 64729
telemt_me_writer_teardown_noop_total 62606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 124217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 125180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 126253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 126854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127335
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.782189
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127335
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 739
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 2057
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 188
telemt_user_connections_total{user="hello"} 8345953
telemt_user_connections_current{user="hello"} 463
telemt_user_octets_from_client{user="hello"} 192723284179 (179.49 GB)
telemt_user_octets_to_client{user="hello"} 3469577663305 (3.16 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 219
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 58934.3 (16h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11234717
telemt_connections_bad_total 668659
telemt_connections_current 868
telemt_connections_me_current 868
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 271189
telemt_upstream_connect_attempt_total 57652
telemt_upstream_connect_success_total 54608
telemt_upstream_connect_fail_total 2025
telemt_upstream_connect_attempts_per_request{bucket="1"} 56633
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18787
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6015
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2025
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7670
telemt_me_reconnect_success_total 1215
telemt_me_reader_eof_total 760
telemt_me_idle_close_by_peer_total 759
telemt_me_route_drop_no_conn_total 25289116
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9324921
telemt_me_endpoint_quarantine_total 440
telemt_me_single_endpoint_outage_enter_total 94
telemt_me_single_endpoint_outage_exit_total 94
telemt_me_single_endpoint_outage_reconnect_attempt_total 179
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 179
telemt_me_single_endpoint_shadow_rotate_total 468
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 27
telemt_desync_total 16307
telemt_desync_full_logged_total 4443
telemt_desync_suppressed_total 11864
telemt_desync_frames_bucket_total{bucket="1_2"} 3090
telemt_desync_frames_bucket_total{bucket="3_10"} 6637
telemt_desync_frames_bucket_total{bucket="gt_10"} 6580
telemt_pool_swap_total 61
telemt_pool_force_close_total 1999
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 484
telemt_me_draining_writers_reap_progress_total 18401
telemt_me_writer_removed_unexpected_total 1117
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2503
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16958
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1692
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16402
telemt_me_writer_teardown_success_total{mode="normal"} 19461
telemt_me_writer_teardown_noop_total 18420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37881
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.734895
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37881
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 484
telemt_me_refill_failed_total 337
telemt_me_writer_restored_same_endpoint_total 788
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 9350799
telemt_user_connections_current{user="hello"} 868
telemt_user_octets_from_client{user="hello"} 87215558766 (81.23 GB)
telemt_user_octets_to_client{user="hello"} 605542628122 (563.96 GB)
telemt_user_msgs_from_client{user="hello"} 68321
telemt_user_msgs_to_client{user="hello"} 57932
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 188660.9 (52h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10988528
telemt_connections_bad_total 946793
telemt_connections_current 802
telemt_connections_me_current 802
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242025
telemt_upstream_connect_attempt_total 112061
telemt_upstream_connect_success_total 110905
telemt_upstream_connect_fail_total 983
telemt_upstream_connect_attempts_per_request{bucket="1"} 111888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 66149
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43158
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1360
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 983
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72879
telemt_me_reconnect_success_total 3073
telemt_me_reader_eof_total 2761
telemt_me_idle_close_by_peer_total 2759
telemt_me_route_drop_no_conn_total 5261732
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8672350
telemt_me_endpoint_quarantine_total 1272
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 45
telemt_me_single_endpoint_outage_reconnect_success_total 43
telemt_me_single_endpoint_quarantine_bypass_total 45
telemt_me_single_endpoint_shadow_rotate_total 1426
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
telemt_me_writers_active_current 43
telemt_desync_total 46219
telemt_desync_full_logged_total 15826
telemt_desync_suppressed_total 30393
telemt_desync_frames_bucket_total{bucket="1_2"} 9392
telemt_desync_frames_bucket_total{bucket="3_10"} 17691
telemt_desync_frames_bucket_total{bucket="gt_10"} 19136
telemt_pool_swap_total 193
telemt_pool_force_close_total 5665
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 663
telemt_me_draining_writers_reap_progress_total 66715
telemt_me_writer_removed_unexpected_total 2790
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6829
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62711
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61050
telemt_me_writer_teardown_success_total{mode="normal"} 69540
telemt_me_writer_teardown_noop_total 66716
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136252
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136256
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.264465
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136256
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 663
telemt_me_refill_failed_total 4297
telemt_me_writer_restored_same_endpoint_total 2592
telemt_me_writer_restored_fallback_total 52
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 146
telemt_user_connections_total{user="hello"} 8675352
telemt_user_connections_current{user="hello"} 802
telemt_user_octets_from_client{user="hello"} 194573003361 (181.21 GB)
telemt_user_octets_to_client{user="hello"} 3315098986228 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 365
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 125497.1 (34h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11692045
telemt_connections_bad_total 482235
telemt_connections_current 508
telemt_connections_me_current 508
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4760341
telemt_upstream_connect_attempt_total 60337
telemt_upstream_connect_success_total 59897
telemt_upstream_connect_fail_total 429
telemt_upstream_connect_attempts_per_request{bucket="1"} 60326
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 218
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 429
telemt_me_reconnect_attempts_total 48956
telemt_me_reconnect_success_total 1811
telemt_me_reader_eof_total 1483
telemt_me_idle_close_by_peer_total 1482
telemt_me_route_drop_no_conn_total 4086911
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5617202
telemt_me_endpoint_quarantine_total 850
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 962
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31574
telemt_desync_full_logged_total 10766
telemt_desync_suppressed_total 20808
telemt_desync_frames_bucket_total{bucket="1_2"} 6283
telemt_desync_frames_bucket_total{bucket="3_10"} 12454
telemt_desync_frames_bucket_total{bucket="gt_10"} 12837
telemt_pool_swap_total 133
telemt_pool_force_close_total 3892
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 45932
telemt_me_writer_removed_unexpected_total 1534
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3780
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43729
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3451
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42040
telemt_me_writer_teardown_success_total{mode="normal"} 47509
telemt_me_writer_teardown_noop_total 45939
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 93448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 93448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 93448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 93448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 93448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 93448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 93448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 93448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 93448
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.688312
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 93448
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 2739
telemt_me_writer_restored_same_endpoint_total 1605
telemt_me_writer_restored_fallback_total 26
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5609727
telemt_user_connections_current{user="hello"} 508
telemt_user_octets_from_client{user="hello"} 119080333336 (110.90 GB)
telemt_user_octets_to_client{user="hello"} 2170913369594 (1.97 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 106468.2 (29h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1519434
telemt_connections_bad_total 36720
telemt_connections_current 431
telemt_connections_me_current 431
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 30605
telemt_upstream_connect_attempt_total 50171
telemt_upstream_connect_success_total 50013
telemt_upstream_connect_fail_total 130
telemt_upstream_connect_attempts_per_request{bucket="1"} 50143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26146
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 788
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 130
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2244
telemt_me_reconnect_success_total 909
telemt_me_reader_eof_total 896
telemt_me_idle_close_by_peer_total 896
telemt_me_route_drop_no_conn_total 517074
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1350394
telemt_me_endpoint_quarantine_total 882
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 878
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 44
telemt_desync_total 8934
telemt_desync_full_logged_total 2615
telemt_desync_suppressed_total 6319
telemt_desync_frames_bucket_total{bucket="1_2"} 2494
telemt_desync_frames_bucket_total{bucket="3_10"} 3414
telemt_desync_frames_bucket_total{bucket="gt_10"} 3026
telemt_pool_swap_total 115
telemt_pool_force_close_total 2945
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 166
telemt_me_draining_writers_reap_progress_total 42415
telemt_me_writer_removed_unexpected_total 864
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3258
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40060
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39470
telemt_me_writer_teardown_success_total{mode="normal"} 43318
telemt_me_writer_teardown_noop_total 42419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85737
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.292641
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85737
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 166
telemt_me_refill_failed_total 74
telemt_me_writer_restored_same_endpoint_total 773
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1346205
telemt_user_connections_current{user="hello"} 431
telemt_user_octets_from_client{user="hello"} 25967394473 (24.18 GB)
telemt_user_octets_to_client{user="hello"} 574665474787 (535.20 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 181
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 188665.4 (52h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13321069
telemt_connections_bad_total 1600736
telemt_connections_current 624
telemt_connections_me_current 624
telemt_handshake_timeouts_total 388682
telemt_upstream_connect_attempt_total 74100
telemt_upstream_connect_success_total 73750
telemt_upstream_connect_fail_total 214
telemt_upstream_connect_attempts_per_request{bucket="1"} 73964
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 214
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2970
telemt_me_reconnect_success_total 1486
telemt_me_reader_eof_total 1470
telemt_me_idle_close_by_peer_total 1470
telemt_me_route_drop_no_conn_total 4482463
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10045358
telemt_me_endpoint_quarantine_total 1345
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1426
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 42054
telemt_desync_full_logged_total 13738
telemt_desync_suppressed_total 28316
telemt_desync_frames_bucket_total{bucket="1_2"} 10168
telemt_desync_frames_bucket_total{bucket="3_10"} 15455
telemt_desync_frames_bucket_total{bucket="gt_10"} 16431
telemt_pool_swap_total 209
telemt_pool_force_close_total 5583
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 675
telemt_me_draining_writers_reap_progress_total 66947
telemt_me_writer_removed_unexpected_total 1408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5292
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 63115
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5409
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61364
telemt_me_writer_teardown_success_total{mode="normal"} 68407
telemt_me_writer_teardown_noop_total 66949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 132746
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 134847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 135223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 135343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 135356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 135356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 135356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 135356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 135356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 135356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 135356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 135356
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.772175
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 135356
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 675
telemt_me_refill_failed_total 80
telemt_me_writer_restored_same_endpoint_total 1303
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 10012072
telemt_user_connections_current{user="hello"} 624
telemt_user_octets_from_client{user="hello"} 194762608144 (181.39 GB)
telemt_user_octets_to_client{user="hello"} 4438518825972 (4.04 TB)
telemt_user_unique_ips_current{user="hello"} 284
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 188661.9 (52h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11634584
telemt_connections_bad_total 1357448
telemt_connections_current 540
telemt_connections_me_current 540
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 311322
telemt_upstream_connect_attempt_total 101598
telemt_upstream_connect_success_total 100709
telemt_upstream_connect_fail_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 101389
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54947
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42782
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 680
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10470
telemt_me_reconnect_success_total 2579
telemt_me_reader_eof_total 2391
telemt_me_idle_close_by_peer_total 2390
telemt_me_seq_mismatch_total 97
telemt_me_route_drop_no_conn_total 5649525
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8955270
telemt_me_endpoint_quarantine_total 1521
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 52
telemt_me_single_endpoint_outage_exit_total 52
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 50
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 1430
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_me_writers_active_current 45
telemt_desync_total 41778
telemt_desync_full_logged_total 13450
telemt_desync_suppressed_total 28328
telemt_desync_frames_bucket_total{bucket="1_2"} 10784
telemt_desync_frames_bucket_total{bucket="3_10"} 15367
telemt_desync_frames_bucket_total{bucket="gt_10"} 15627
telemt_pool_swap_total 199
telemt_pool_force_close_total 5361
telemt_pool_stale_pick_total 372
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 67001
telemt_me_writer_removed_unexpected_total 2433
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6641
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 62877
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4890
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61640
telemt_me_writer_teardown_success_total{mode="normal"} 69518
telemt_me_writer_teardown_noop_total 67006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 136474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 136524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 136524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 136524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 136524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 136524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 136524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 136524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 136524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 136524
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.462657
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 136524
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 408
telemt_me_writer_restored_same_endpoint_total 2075
telemt_me_writer_restored_fallback_total 132
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 8959869
telemt_user_connections_current{user="hello"} 540
telemt_user_octets_from_client{user="hello"} 157344317444 (146.54 GB)
telemt_user_octets_to_client{user="hello"} 3488393215630 (3.17 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 259
telemt_user_unique_ips_recent_window{user="hello"} 67
```