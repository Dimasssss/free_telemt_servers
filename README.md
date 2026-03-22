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

# Server Metrics 2026-03-22 17:40:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 74067.2 (20h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2675447
telemt_connections_bad_total 146444
telemt_connections_current 1490
telemt_connections_me_current 1490
telemt_handshake_timeouts_total 91956
telemt_upstream_connect_attempt_total 27292
telemt_upstream_connect_success_total 27291
telemt_upstream_connect_attempts_per_request{bucket="1"} 27291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17740
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 61
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1119
telemt_me_reconnect_success_total 471
telemt_me_reader_eof_total 473
telemt_me_idle_close_by_peer_total 473
telemt_me_route_drop_no_conn_total 2211663
telemt_me_route_drop_channel_closed_total 916
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2282821
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 578
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
telemt_me_writers_active_current 44
telemt_desync_total 10570
telemt_desync_full_logged_total 3345
telemt_desync_suppressed_total 7225
telemt_desync_frames_bucket_total{bucket="1_2"} 2830
telemt_desync_frames_bucket_total{bucket="3_10"} 3934
telemt_desync_frames_bucket_total{bucket="gt_10"} 3806
telemt_pool_swap_total 82
telemt_pool_force_close_total 2542
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 517
telemt_me_draining_writers_reap_progress_total 24920
telemt_me_writer_removed_unexpected_total 459
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1826
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23323
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2490
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22378
telemt_me_writer_teardown_success_total{mode="normal"} 25149
telemt_me_writer_teardown_noop_total 24930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50079
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 246.944912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50079
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 517
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 416
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2279048
telemt_user_connections_current{user="hello"} 1490
telemt_user_octets_from_client{user="hello"} 33624103284 (31.31 GB)
telemt_user_octets_to_client{user="hello"} 602500869952 (561.12 GB)
telemt_user_unique_ips_current{user="hello"} 550
telemt_user_unique_ips_recent_window{user="hello"} 236
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 87433.3 (24h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3687110
telemt_connections_bad_total 334228
telemt_connections_current 1139
telemt_connections_me_current 1139
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 93377
telemt_upstream_connect_attempt_total 54026
telemt_upstream_connect_success_total 53353
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 53946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6256
telemt_me_reconnect_success_total 2263
telemt_me_reader_eof_total 2195
telemt_me_idle_close_by_peer_total 2195
telemt_me_route_drop_no_conn_total 3556385
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2924751
telemt_me_endpoint_quarantine_total 694
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 674
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 11505
telemt_desync_full_logged_total 6429
telemt_desync_suppressed_total 5076
telemt_desync_frames_bucket_total{bucket="1_2"} 2676
telemt_desync_frames_bucket_total{bucket="3_10"} 4517
telemt_desync_frames_bucket_total{bucket="gt_10"} 4312
telemt_pool_swap_total 83
telemt_pool_force_close_total 2463
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 210
telemt_me_draining_writers_reap_progress_total 34683
telemt_me_writer_removed_unexpected_total 2146
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4143
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32696
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2101
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32220
telemt_me_writer_teardown_success_total{mode="normal"} 36839
telemt_me_writer_teardown_noop_total 34683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70872
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71522
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.237546
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71522
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 210
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 1954
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2935953
telemt_user_connections_current{user="hello"} 1139
telemt_user_octets_from_client{user="hello"} 37599911563 (35.02 GB)
telemt_user_octets_to_client{user="hello"} 668610344314 (622.69 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 621
telemt_user_unique_ips_recent_window{user="hello"} 297
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 162293.2 (45h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15574930
telemt_connections_bad_total 1489176
telemt_connections_current 2048
telemt_connections_me_current 2048
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 381690
telemt_upstream_connect_attempt_total 72913
telemt_upstream_connect_success_total 72816
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 72833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2703
telemt_me_reconnect_success_total 1391
telemt_me_reader_eof_total 1329
telemt_me_idle_close_by_peer_total 1327
telemt_me_route_drop_no_conn_total 13867824
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12415667
telemt_me_endpoint_quarantine_total 1020
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1209
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
telemt_me_writers_active_current 43
telemt_desync_total 50859
telemt_desync_full_logged_total 15965
telemt_desync_suppressed_total 34894
telemt_desync_frames_bucket_total{bucket="1_2"} 11352
telemt_desync_frames_bucket_total{bucket="3_10"} 19849
telemt_desync_frames_bucket_total{bucket="gt_10"} 19658
telemt_pool_swap_total 175
telemt_pool_force_close_total 5937
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 959
telemt_me_draining_writers_reap_progress_total 53362
telemt_me_writer_removed_unexpected_total 1283
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4667
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49269
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5475
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47425
telemt_me_writer_teardown_success_total{mode="normal"} 53936
telemt_me_writer_teardown_noop_total 53412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107309
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107348
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 304.650277
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107348
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 959
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1196
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12416612
telemt_user_connections_current{user="hello"} 2048
telemt_user_octets_from_client{user="hello"} 179221255549 (166.91 GB)
telemt_user_octets_to_client{user="hello"} 3234449552567 (2.94 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 827
telemt_user_unique_ips_recent_window{user="hello"} 329
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 162304.5 (45h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11228944
telemt_connections_bad_total 1095614
telemt_connections_current 1520
telemt_connections_me_current 1520
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 336582
telemt_upstream_connect_attempt_total 85322
telemt_upstream_connect_success_total 84131
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 84969
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34530
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 4043
telemt_me_reconnect_success_total 1674
telemt_me_reader_eof_total 1542
telemt_me_idle_close_by_peer_total 1542
telemt_me_route_drop_no_conn_total 4409683
telemt_me_route_drop_channel_closed_total 488
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8369476
telemt_me_endpoint_quarantine_total 1026
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1227
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
telemt_me_writers_active_current 43
telemt_desync_total 37220
telemt_desync_full_logged_total 12523
telemt_desync_suppressed_total 24697
telemt_desync_frames_bucket_total{bucket="1_2"} 9153
telemt_desync_frames_bucket_total{bucket="3_10"} 14331
telemt_desync_frames_bucket_total{bucket="gt_10"} 13736
telemt_pool_swap_total 172
telemt_pool_force_close_total 5364
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 51777
telemt_me_writer_removed_unexpected_total 1582
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4805
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48397
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 498
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46413
telemt_me_writer_teardown_success_total{mode="normal"} 53202
telemt_me_writer_teardown_noop_total 51800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 103832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104917
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105000
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105002
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 101.944534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105002
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 1434
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8307977
telemt_user_connections_current{user="hello"} 1520
telemt_user_octets_from_client{user="hello"} 207646366905 (193.39 GB)
telemt_user_octets_to_client{user="hello"} 3744258381134 (3.41 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 560
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 162259.1 (45h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10588249
telemt_connections_bad_total 913096
telemt_connections_current 1431
telemt_connections_me_current 1431
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 339094
telemt_upstream_connect_attempt_total 70454
telemt_upstream_connect_success_total 69460
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 69642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33051
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1410
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2099
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4787
telemt_me_reconnect_success_total 1932
telemt_me_reader_eof_total 1684
telemt_me_idle_close_by_peer_total 1683
telemt_me_route_drop_no_conn_total 5173912
telemt_me_route_drop_channel_closed_total 368
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7990628
telemt_me_endpoint_quarantine_total 1107
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1195
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36722
telemt_desync_full_logged_total 12151
telemt_desync_suppressed_total 24571
telemt_desync_frames_bucket_total{bucket="1_2"} 9286
telemt_desync_frames_bucket_total{bucket="3_10"} 14046
telemt_desync_frames_bucket_total{bucket="gt_10"} 13390
telemt_pool_swap_total 170
telemt_pool_force_close_total 5290
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 52077
telemt_me_writer_removed_unexpected_total 1826
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5219
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48597
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4748
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46787
telemt_me_writer_teardown_success_total{mode="normal"} 53816
telemt_me_writer_teardown_noop_total 52148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 103873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105964
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3172.208029
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105964
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1671
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 7983410
telemt_user_connections_current{user="hello"} 1431
telemt_user_octets_from_client{user="hello"} 184536505721 (171.86 GB)
telemt_user_octets_to_client{user="hello"} 3321729090501 (3.02 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 495
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 32538.7 (9h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10399209
telemt_connections_bad_total 636338
telemt_connections_current 2361
telemt_connections_me_current 2361
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 203416
telemt_upstream_connect_attempt_total 41436
telemt_upstream_connect_success_total 39344
telemt_upstream_connect_fail_total 1482
telemt_upstream_connect_attempts_per_request{bucket="1"} 40826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20274
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11765
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5916
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1482
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6160
telemt_me_reconnect_success_total 788
telemt_me_reader_eof_total 491
telemt_me_idle_close_by_peer_total 491
telemt_me_route_drop_no_conn_total 25035142
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8645458
telemt_me_endpoint_quarantine_total 209
telemt_me_single_endpoint_outage_enter_total 59
telemt_me_single_endpoint_outage_exit_total 59
telemt_me_single_endpoint_outage_reconnect_attempt_total 110
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 110
telemt_me_single_endpoint_shadow_rotate_total 256
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 13709
telemt_desync_full_logged_total 3569
telemt_desync_suppressed_total 10140
telemt_desync_frames_bucket_total{bucket="1_2"} 2532
telemt_desync_frames_bucket_total{bucket="3_10"} 5554
telemt_desync_frames_bucket_total{bucket="gt_10"} 5623
telemt_pool_swap_total 32
telemt_pool_force_close_total 1186
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 9111
telemt_me_writer_removed_unexpected_total 694
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1439
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8328
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7925
telemt_me_writer_teardown_success_total{mode="normal"} 9767
telemt_me_writer_teardown_noop_total 9116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 17848
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18883
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 40.895821
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18883
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 297
telemt_me_writer_restored_same_endpoint_total 528
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 162
telemt_user_connections_total{user="hello"} 8667183
telemt_user_connections_current{user="hello"} 2361
telemt_user_octets_from_client{user="hello"} 71803911223 (66.87 GB)
telemt_user_octets_to_client{user="hello"} 368311546957 (343.02 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 854
telemt_user_unique_ips_recent_window{user="hello"} 318
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 162265.3 (45h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10409620
telemt_connections_bad_total 875649
telemt_connections_current 1632
telemt_connections_me_current 1632
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 230973
telemt_upstream_connect_attempt_total 99186
telemt_upstream_connect_success_total 98157
telemt_upstream_connect_fail_total 874
telemt_upstream_connect_attempts_per_request{bucket="1"} 99031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60372
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36230
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1317
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 874
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72101
telemt_me_reconnect_success_total 2674
telemt_me_reader_eof_total 2376
telemt_me_idle_close_by_peer_total 2374
telemt_me_route_drop_no_conn_total 5110820
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8213141
telemt_me_endpoint_quarantine_total 1089
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1210
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
telemt_desync_total 43165
telemt_desync_full_logged_total 14739
telemt_desync_suppressed_total 28426
telemt_desync_frames_bucket_total{bucket="1_2"} 8789
telemt_desync_frames_bucket_total{bucket="3_10"} 16650
telemt_desync_frames_bucket_total{bucket="gt_10"} 17726
telemt_pool_swap_total 166
telemt_pool_force_close_total 4935
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 617
telemt_me_draining_writers_reap_progress_total 55202
telemt_me_writer_removed_unexpected_total 2417
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5908
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51734
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4249
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 686
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50267
telemt_me_writer_teardown_success_total{mode="normal"} 57642
telemt_me_writer_teardown_noop_total 55203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 112801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 112835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 112838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 112838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 112841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 112845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 112845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 112845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 112845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 112845
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.600296
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 112845
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 617
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2242
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8216835
telemt_user_connections_current{user="hello"} 1632
telemt_user_octets_from_client{user="hello"} 186672131729 (173.85 GB)
telemt_user_octets_to_client{user="hello"} 3102732294904 (2.82 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 594
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 99101.4 (27h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10879385
telemt_connections_bad_total 415389
telemt_connections_current 2089
telemt_connections_me_current 2089
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4533396
telemt_upstream_connect_attempt_total 47344
telemt_upstream_connect_success_total 46989
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 47334
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26147
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_reconnect_attempts_total 48222
telemt_me_reconnect_success_total 1564
telemt_me_reader_eof_total 1224
telemt_me_idle_close_by_peer_total 1223
telemt_me_route_drop_no_conn_total 3961931
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5226008
telemt_me_endpoint_quarantine_total 639
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 743
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_writers_warm_current 37
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29089
telemt_desync_full_logged_total 9855
telemt_desync_suppressed_total 19234
telemt_desync_frames_bucket_total{bucket="1_2"} 5858
telemt_desync_frames_bucket_total{bucket="3_10"} 11488
telemt_desync_frames_bucket_total{bucket="gt_10"} 11743
telemt_pool_swap_total 104
telemt_pool_force_close_total 3194
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 332
telemt_me_draining_writers_reap_progress_total 34090
telemt_me_writer_removed_unexpected_total 1284
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3051
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32356
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2773
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 421
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30896
telemt_me_writer_teardown_success_total{mode="normal"} 35407
telemt_me_writer_teardown_noop_total 34097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69008
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69504
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.083066
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69504
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 332
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1390
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5219281
telemt_user_connections_current{user="hello"} 2089
telemt_user_octets_from_client{user="hello"} 112853128228 (105.10 GB)
telemt_user_octets_to_client{user="hello"} 1983174650138 (1.80 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 767
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 80072.1 (22h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1127383
telemt_connections_bad_total 18249
telemt_connections_current 1108
telemt_connections_me_current 1108
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 21026
telemt_upstream_connect_attempt_total 38729
telemt_upstream_connect_success_total 38617
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 38704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17500
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 601
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_reconnect_attempts_total 1749
telemt_me_reconnect_success_total 742
telemt_me_reader_eof_total 717
telemt_me_idle_close_by_peer_total 717
telemt_me_route_drop_no_conn_total 394588
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1003399
telemt_me_endpoint_quarantine_total 676
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 658
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5773
telemt_desync_full_logged_total 1761
telemt_desync_suppressed_total 4012
telemt_desync_frames_bucket_total{bucket="1_2"} 1364
telemt_desync_frames_bucket_total{bucket="3_10"} 2269
telemt_desync_frames_bucket_total{bucket="gt_10"} 2140
telemt_pool_swap_total 85
telemt_pool_force_close_total 2178
telemt_me_writer_close_signal_drop_total 125
telemt_me_draining_writers_reap_progress_total 32127
telemt_me_writer_removed_unexpected_total 692
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2485
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30361
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2095
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29949
telemt_me_writer_teardown_success_total{mode="normal"} 32846
telemt_me_writer_teardown_noop_total 32130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64976
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.832024
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64976
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 125
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 632
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 999805
telemt_user_connections_current{user="hello"} 1108
telemt_user_octets_from_client{user="hello"} 18427877401 (17.16 GB)
telemt_user_octets_to_client{user="hello"} 430959187587 (401.36 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 418
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 162269.8 (45h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12692263
telemt_connections_bad_total 1471735
telemt_connections_current 1919
telemt_connections_me_current 1919
telemt_handshake_timeouts_total 355788
telemt_upstream_connect_attempt_total 61086
telemt_upstream_connect_success_total 60791
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 60979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30726
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_reconnect_attempts_total 2407
telemt_me_reconnect_success_total 1271
telemt_me_reader_eof_total 1234
telemt_me_idle_close_by_peer_total 1234
telemt_me_route_drop_no_conn_total 4250536
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9601950
telemt_me_endpoint_quarantine_total 1085
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1213
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
telemt_desync_total 39445
telemt_desync_full_logged_total 12873
telemt_desync_suppressed_total 26572
telemt_desync_frames_bucket_total{bucket="1_2"} 9397
telemt_desync_frames_bucket_total{bucket="3_10"} 14592
telemt_desync_frames_bucket_total{bucket="gt_10"} 15456
telemt_pool_swap_total 180
telemt_pool_force_close_total 4965
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 635
telemt_me_draining_writers_reap_progress_total 54964
telemt_me_writer_removed_unexpected_total 1186
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4533
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51651
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4791
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49999
telemt_me_writer_teardown_success_total{mode="normal"} 56184
telemt_me_writer_teardown_noop_total 54966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111150
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.523955
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111150
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 635
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1110
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9571034
telemt_user_connections_current{user="hello"} 1919
telemt_user_octets_from_client{user="hello"} 187589571568 (174.71 GB)
telemt_user_octets_to_client{user="hello"} 4225981266380 (3.84 TB)
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 162276.2 (45h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11010066
telemt_connections_bad_total 1230435
telemt_connections_current 1578
telemt_connections_me_current 1578
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 285963
telemt_upstream_connect_attempt_total 87156
telemt_upstream_connect_success_total 86408
telemt_upstream_connect_fail_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 86986
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35990
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2050
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 578
telemt_me_reconnect_attempts_total 9157
telemt_me_reconnect_success_total 2177
telemt_me_reader_eof_total 2031
telemt_me_idle_close_by_peer_total 2031
telemt_me_seq_mismatch_total 76
telemt_me_route_drop_no_conn_total 5492626
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8517948
telemt_me_endpoint_quarantine_total 1238
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1216
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 38775
telemt_desync_full_logged_total 12522
telemt_desync_suppressed_total 26253
telemt_desync_frames_bucket_total{bucket="1_2"} 9650
telemt_desync_frames_bucket_total{bucket="3_10"} 14439
telemt_desync_frames_bucket_total{bucket="gt_10"} 14686
telemt_pool_swap_total 171
telemt_pool_force_close_total 4793
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 618
telemt_me_draining_writers_reap_progress_total 54615
telemt_me_writer_removed_unexpected_total 2058
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5718
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51025
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4337
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49822
telemt_me_writer_teardown_success_total{mode="normal"} 56743
telemt_me_writer_teardown_noop_total 54620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111363
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.751937
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111363
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 618
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1771
telemt_me_writer_restored_fallback_total 104
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 8523796
telemt_user_connections_current{user="hello"} 1578
telemt_user_octets_from_client{user="hello"} 149769172121 (139.48 GB)
telemt_user_octets_to_client{user="hello"} 3265563729243 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 207
```