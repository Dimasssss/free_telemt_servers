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

# Server Metrics 2026-03-21 14:57:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 66100.4 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2306623
telemt_connections_bad_total 114071
telemt_connections_current 1543
telemt_connections_me_current 1543
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 76053
telemt_upstream_connect_attempt_total 28355
telemt_upstream_connect_success_total 28230
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28312
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11785
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16358
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1639
telemt_me_reconnect_success_total 651
telemt_me_reader_eof_total 623
telemt_me_idle_close_by_peer_total 623
telemt_me_route_drop_no_conn_total 1960437
telemt_me_route_drop_channel_closed_total 617
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1844342
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 466
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 517
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
telemt_desync_total 7178
telemt_desync_full_logged_total 2471
telemt_desync_suppressed_total 4707
telemt_desync_frames_bucket_total{bucket="1_2"} 1586
telemt_desync_frames_bucket_total{bucket="3_10"} 2734
telemt_desync_frames_bucket_total{bucket="gt_10"} 2858
telemt_pool_swap_total 71
telemt_pool_force_close_total 2156
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 488
telemt_me_draining_writers_reap_progress_total 22633
telemt_me_writer_removed_unexpected_total 603
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1947
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21073
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 116
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20477
telemt_me_writer_teardown_success_total{mode="normal"} 23020
telemt_me_writer_teardown_noop_total 22639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45659
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.089444
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45659
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 488
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 559
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1845919
telemt_user_connections_current{user="hello"} 1543
telemt_user_octets_from_client{user="hello"} 26240757329 (24.44 GB)
telemt_user_octets_to_client{user="hello"} 458130628474 (426.67 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 222
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 193.2 (0h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2245
telemt_connections_bad_total 6
telemt_connections_current 456
telemt_connections_me_current 456
telemt_handshake_timeouts_total 20
telemt_upstream_connect_attempt_total 177
telemt_upstream_connect_success_total 174
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 176
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 97
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 76
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 3
telemt_me_route_drop_no_conn_total 613
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2099
telemt_me_endpoint_quarantine_total 1
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_desync_total 11
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 5
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_force_close_total 1
telemt_me_draining_writers_reap_progress_total 88
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 87
telemt_me_writer_teardown_success_total{mode="normal"} 88
telemt_me_writer_teardown_noop_total 88
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 176
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.001118
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 176
telemt_user_connections_total{user="hello"} 2098
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 16132504 (15.39 MB)
telemt_user_octets_to_client{user="hello"} 698416248 (666.06 MB)
telemt_user_unique_ips_current{user="hello"} 290
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 66098.1 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4561659
telemt_connections_bad_total 410126
telemt_connections_current 4932
telemt_connections_me_current 4932
telemt_handshake_timeouts_total 167872
telemt_upstream_connect_attempt_total 24650
telemt_upstream_connect_success_total 24598
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13384
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 99
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1109
telemt_me_reconnect_success_total 568
telemt_me_reader_eof_total 570
telemt_me_idle_close_by_peer_total 570
telemt_me_route_drop_no_conn_total 2506350
telemt_me_route_drop_channel_closed_total 43
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3725311
telemt_me_endpoint_quarantine_total 421
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 500
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
telemt_me_writers_active_current 43
telemt_desync_total 15303
telemt_desync_full_logged_total 5161
telemt_desync_suppressed_total 10142
telemt_desync_frames_bucket_total{bucket="1_2"} 3269
telemt_desync_frames_bucket_total{bucket="3_10"} 6035
telemt_desync_frames_bucket_total{bucket="gt_10"} 5999
telemt_pool_swap_total 70
telemt_pool_force_close_total 2265
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 357
telemt_me_draining_writers_reap_progress_total 22364
telemt_me_writer_removed_unexpected_total 551
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1962
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20735
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2071
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 194
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20099
telemt_me_writer_teardown_success_total{mode="normal"} 22697
telemt_me_writer_teardown_noop_total 22396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42693
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 74.582856
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 357
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 510
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 3720694
telemt_user_connections_current{user="hello"} 4932
telemt_user_octets_from_client{user="hello"} 60448816144 (56.30 GB)
telemt_user_octets_to_client{user="hello"} 1242079260500 (1.13 TB)
telemt_user_unique_ips_current{user="hello"} 1880
telemt_user_unique_ips_recent_window{user="hello"} 591
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 66099.1 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3724124
telemt_connections_bad_total 409368
telemt_connections_current 3736
telemt_connections_me_current 3736
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 135649
telemt_upstream_connect_attempt_total 29061
telemt_upstream_connect_success_total 28782
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 28919
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 484
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1251
telemt_me_reconnect_success_total 568
telemt_me_reader_eof_total 539
telemt_me_idle_close_by_peer_total 539
telemt_me_route_drop_no_conn_total 1159553
telemt_me_route_drop_channel_closed_total 91
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2714840
telemt_me_endpoint_quarantine_total 427
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 506
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
telemt_desync_total 12615
telemt_desync_full_logged_total 4247
telemt_desync_suppressed_total 8368
telemt_desync_frames_bucket_total{bucket="1_2"} 3158
telemt_desync_frames_bucket_total{bucket="3_10"} 4871
telemt_desync_frames_bucket_total{bucket="gt_10"} 4586
telemt_pool_swap_total 72
telemt_pool_force_close_total 2074
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 204
telemt_me_draining_writers_reap_progress_total 21589
telemt_me_writer_removed_unexpected_total 523
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1837
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20277
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1936
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 138
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19515
telemt_me_writer_teardown_success_total{mode="normal"} 22114
telemt_me_writer_teardown_noop_total 21590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43704
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.312229
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43704
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 204
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 481
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 2714816
telemt_user_connections_current{user="hello"} 3736
telemt_user_octets_from_client{user="hello"} 51070468101 (47.56 GB)
telemt_user_octets_to_client{user="hello"} 1267152203899 (1.15 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1437
telemt_user_unique_ips_recent_window{user="hello"} 496
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 66063.4 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3629945
telemt_connections_bad_total 386257
telemt_connections_current 3676
telemt_connections_me_current 3676
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 108864
telemt_upstream_connect_attempt_total 34291
telemt_upstream_connect_success_total 34056
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 34189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18143
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14778
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 850
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1308
telemt_me_reconnect_success_total 636
telemt_me_reader_eof_total 579
telemt_me_idle_close_by_peer_total 579
telemt_me_route_drop_no_conn_total 1126375
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2674753
telemt_me_endpoint_quarantine_total 476
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 496
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
telemt_desync_total 12442
telemt_desync_full_logged_total 4162
telemt_desync_suppressed_total 8280
telemt_desync_frames_bucket_total{bucket="1_2"} 3118
telemt_desync_frames_bucket_total{bucket="3_10"} 4680
telemt_desync_frames_bucket_total{bucket="gt_10"} 4644
telemt_pool_swap_total 70
telemt_pool_force_close_total 2003
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 227
telemt_me_draining_writers_reap_progress_total 23000
telemt_me_writer_removed_unexpected_total 551
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1940
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21647
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1825
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 178
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20997
telemt_me_writer_teardown_success_total{mode="normal"} 23587
telemt_me_writer_teardown_noop_total 23005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46592
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.898960
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46592
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 227
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 553
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2678711
telemt_user_connections_current{user="hello"} 3676
telemt_user_octets_from_client{user="hello"} 57864370557 (53.89 GB)
telemt_user_octets_to_client{user="hello"} 1256104192280 (1.14 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1394
telemt_user_unique_ips_recent_window{user="hello"} 511
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 66102.6 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12477531
telemt_connections_bad_total 818831
telemt_connections_current 5786
telemt_connections_me_current 5786
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 384554
telemt_upstream_connect_attempt_total 115476
telemt_upstream_connect_success_total 105602
telemt_upstream_connect_fail_total 8847
telemt_upstream_connect_attempts_per_request{bucket="1"} 114449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74138
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8847
telemt_me_keepalive_timeout_total 87
telemt_me_reconnect_attempts_total 3837
telemt_me_reconnect_success_total 1375
telemt_me_reader_eof_total 962
telemt_me_idle_close_by_peer_total 961
telemt_me_route_drop_no_conn_total 23636868
telemt_me_route_drop_channel_closed_total 78
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10237756
telemt_me_endpoint_quarantine_total 509
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 517
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
telemt_me_writers_active_current 46
telemt_desync_total 18212
telemt_desync_full_logged_total 5762
telemt_desync_suppressed_total 12450
telemt_desync_frames_bucket_total{bucket="1_2"} 3984
telemt_desync_frames_bucket_total{bucket="3_10"} 7976
telemt_desync_frames_bucket_total{bucket="gt_10"} 6252
telemt_pool_swap_total 67
telemt_pool_force_close_total 2175
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 471
telemt_me_draining_writers_reap_progress_total 21328
telemt_me_writer_removed_unexpected_total 1323
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2827
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19621
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1825
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 350
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19153
telemt_me_writer_teardown_success_total{mode="normal"} 22448
telemt_me_writer_teardown_noop_total 21338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43786
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 168.402171
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43786
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 471
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 958
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 10313821
telemt_user_connections_current{user="hello"} 5786
telemt_user_octets_from_client{user="hello"} 74538832541 (69.42 GB)
telemt_user_octets_to_client{user="hello"} 780777978533 (727.16 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2014
telemt_user_unique_ips_recent_window{user="hello"} 1141
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 66070.1 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3657838
telemt_connections_bad_total 411528
telemt_connections_current 3871
telemt_connections_me_current 3871
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 80239
telemt_upstream_connect_attempt_total 27977
telemt_upstream_connect_success_total 27669
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 27933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13214
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_reconnect_attempts_total 2671
telemt_me_reconnect_success_total 968
telemt_me_reader_eof_total 962
telemt_me_idle_close_by_peer_total 962
telemt_me_route_drop_no_conn_total 1523639
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2810520
telemt_me_endpoint_quarantine_total 413
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 498
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
telemt_desync_total 13421
telemt_desync_full_logged_total 4669
telemt_desync_suppressed_total 8752
telemt_desync_frames_bucket_total{bucket="1_2"} 2593
telemt_desync_frames_bucket_total{bucket="3_10"} 5310
telemt_desync_frames_bucket_total{bucket="gt_10"} 5518
telemt_pool_swap_total 66
telemt_pool_force_close_total 1918
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 23481
telemt_me_writer_removed_unexpected_total 933
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2309
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22136
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1663
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 255
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21563
telemt_me_writer_teardown_success_total{mode="normal"} 24445
telemt_me_writer_teardown_noop_total 23482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 47886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47927
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.322801
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47927
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 829
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2794229
telemt_user_connections_current{user="hello"} 3871
telemt_user_octets_from_client{user="hello"} 72175111024 (67.22 GB)
telemt_user_octets_to_client{user="hello"} 1176386684654 (1.07 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1461
telemt_user_unique_ips_recent_window{user="hello"} 526
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 2905.7 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466888
telemt_connections_bad_total 10388
telemt_connections_current 3372
telemt_connections_me_current 3372
telemt_handshake_timeouts_total 239192
telemt_upstream_connect_attempt_total 1195
telemt_upstream_connect_success_total 1166
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 1189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 525
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 627
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_reconnect_attempts_total 197
telemt_me_reconnect_success_total 67
telemt_me_reader_eof_total 59
telemt_me_idle_close_by_peer_total 59
telemt_me_route_drop_no_conn_total 180907
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203478
telemt_me_endpoint_quarantine_total 14
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 26
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
telemt_me_writers_active_current 48
telemt_desync_total 862
telemt_desync_full_logged_total 295
telemt_desync_suppressed_total 567
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 339
telemt_desync_frames_bucket_total{bucket="gt_10"} 380
telemt_pool_swap_total 2
telemt_pool_force_close_total 57
telemt_me_writer_close_signal_drop_total 5
telemt_me_draining_writers_reap_progress_total 924
telemt_me_writer_removed_unexpected_total 60
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 874
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 867
telemt_me_writer_teardown_success_total{mode="normal"} 984
telemt_me_writer_teardown_noop_total 924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1873
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1908
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.261028
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1908
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 5
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 59
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 203283
telemt_user_connections_current{user="hello"} 3372
telemt_user_octets_from_client{user="hello"} 5084504808 (4.74 GB)
telemt_user_octets_to_client{user="hello"} 77416975800 (72.10 GB)
telemt_user_unique_ips_current{user="hello"} 1485
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 64056.0 (17h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1169379
telemt_connections_bad_total 136690
telemt_connections_current 798
telemt_connections_me_current 798
telemt_handshake_timeouts_total 411729
telemt_upstream_connect_attempt_total 29856
telemt_upstream_connect_success_total 29849
telemt_upstream_connect_attempts_per_request{bucket="1"} 29849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1276
telemt_me_reconnect_success_total 509
telemt_me_reader_eof_total 508
telemt_me_idle_close_by_peer_total 508
telemt_me_route_drop_no_conn_total 253500
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 548881
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 535
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
telemt_me_writers_active_current 68
telemt_me_writers_warm_current 19
telemt_desync_total 3501
telemt_desync_full_logged_total 1284
telemt_desync_suppressed_total 2217
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 1252
telemt_desync_frames_bucket_total{bucket="gt_10"} 1611
telemt_pool_swap_total 70
telemt_pool_force_close_total 1603
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 26717
telemt_me_writer_removed_unexpected_total 481
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1977
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25233
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25114
telemt_me_writer_teardown_success_total{mode="normal"} 27210
telemt_me_writer_teardown_noop_total 26717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53286
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 53927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 53927
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.939597
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 53927
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 420
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 548574
telemt_user_connections_current{user="hello"} 798
telemt_user_octets_from_client{user="hello"} 11297898647 (10.52 GB)
telemt_user_octets_to_client{user="hello"} 208351609077 (194.04 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 66074.6 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4013146
telemt_connections_bad_total 367984
telemt_connections_current 4541
telemt_connections_me_current 4541
telemt_handshake_timeouts_total 127937
telemt_upstream_connect_attempt_total 26543
telemt_upstream_connect_success_total 26433
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 26509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13134
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13263
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 1130
telemt_me_reconnect_success_total 600
telemt_me_reader_eof_total 565
telemt_me_idle_close_by_peer_total 565
telemt_me_route_drop_no_conn_total 1216838
telemt_me_route_drop_channel_closed_total 31
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3191544
telemt_me_endpoint_quarantine_total 488
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 506
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
telemt_me_writers_active_current 40
telemt_desync_total 12609
telemt_desync_full_logged_total 4158
telemt_desync_suppressed_total 8451
telemt_desync_frames_bucket_total{bucket="1_2"} 2974
telemt_desync_frames_bucket_total{bucket="3_10"} 4709
telemt_desync_frames_bucket_total{bucket="gt_10"} 4926
telemt_pool_swap_total 73
telemt_pool_force_close_total 1908
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 215
telemt_me_draining_writers_reap_progress_total 23823
telemt_me_writer_removed_unexpected_total 555
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1894
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22484
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1867
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21915
telemt_me_writer_teardown_success_total{mode="normal"} 24378
telemt_me_writer_teardown_noop_total 23823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48201
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.584780
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48201
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 215
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 531
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 3183271
telemt_user_connections_current{user="hello"} 4541
telemt_user_octets_from_client{user="hello"} 65055176400 (60.59 GB)
telemt_user_octets_to_client{user="hello"} 1499801910288 (1.36 TB)
telemt_user_unique_ips_current{user="hello"} 1574
telemt_user_unique_ips_recent_window{user="hello"} 609
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 66071.3 (18h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3577272
telemt_connections_bad_total 309784
telemt_connections_current 3893
telemt_connections_me_current 3893
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 108132
telemt_upstream_connect_attempt_total 42941
telemt_upstream_connect_success_total 42652
telemt_upstream_connect_fail_total 238
telemt_upstream_connect_attempts_per_request{bucket="1"} 42890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15093
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 600
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 238
telemt_me_reconnect_attempts_total 3629
telemt_me_reconnect_success_total 807
telemt_me_reader_eof_total 713
telemt_me_idle_close_by_peer_total 713
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1294669
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2880141
telemt_me_endpoint_quarantine_total 550
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 504
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
telemt_desync_total 11168
telemt_desync_full_logged_total 3799
telemt_desync_suppressed_total 7369
telemt_desync_frames_bucket_total{bucket="1_2"} 2787
telemt_desync_frames_bucket_total{bucket="3_10"} 4146
telemt_desync_frames_bucket_total{bucket="gt_10"} 4235
telemt_pool_swap_total 71
telemt_pool_force_close_total 1847
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 207
telemt_me_draining_writers_reap_progress_total 23176
telemt_me_writer_removed_unexpected_total 726
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2240
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21693
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1699
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 148
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21329
telemt_me_writer_teardown_success_total{mode="normal"} 23933
telemt_me_writer_teardown_noop_total 23177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47110
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.854531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47110
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 207
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 627
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2888877
telemt_user_connections_current{user="hello"} 3893
telemt_user_octets_from_client{user="hello"} 51893178961 (48.33 GB)
telemt_user_octets_to_client{user="hello"} 1242824284312 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1492
telemt_user_unique_ips_recent_window{user="hello"} 507
```