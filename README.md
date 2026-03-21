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

# Server Metrics 2026-03-21 20:38:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 86571.3 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3083793
telemt_connections_bad_total 179944
telemt_connections_current 1022
telemt_connections_me_current 1022
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 96419
telemt_upstream_connect_attempt_total 35405
telemt_upstream_connect_success_total 35256
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 35362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14124
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 56
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1928
telemt_me_reconnect_success_total 766
telemt_me_reader_eof_total 735
telemt_me_idle_close_by_peer_total 735
telemt_me_route_drop_no_conn_total 2624862
telemt_me_route_drop_channel_closed_total 845
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2494893
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 590
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 674
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
telemt_me_writers_active_current 44
telemt_desync_total 9983
telemt_desync_full_logged_total 3483
telemt_desync_suppressed_total 6500
telemt_desync_frames_bucket_total{bucket="1_2"} 2168
telemt_desync_frames_bucket_total{bucket="3_10"} 3741
telemt_desync_frames_bucket_total{bucket="gt_10"} 4074
telemt_pool_swap_total 94
telemt_pool_force_close_total 2815
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 29020
telemt_me_writer_removed_unexpected_total 717
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2441
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27036
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2675
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 140
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26205
telemt_me_writer_teardown_success_total{mode="normal"} 29477
telemt_me_writer_teardown_noop_total 29028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58505
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 300.077808
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58505
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 658
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2494517
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 36926521533 (34.39 GB)
telemt_user_octets_to_client{user="hello"} 636134459374 (592.45 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 419
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 11709.9 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 466212
telemt_connections_bad_total 22152
telemt_connections_current 1505
telemt_connections_me_current 1505
telemt_handshake_timeouts_total 16464
telemt_upstream_connect_attempt_total 4594
telemt_upstream_connect_success_total 4503
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 4582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2002
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2485
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_reconnect_attempts_total 309
telemt_me_reconnect_success_total 143
telemt_me_reader_eof_total 121
telemt_me_idle_close_by_peer_total 121
telemt_me_route_drop_no_conn_total 275731
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 379386
telemt_me_endpoint_quarantine_total 86
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 92
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
telemt_me_writers_active_current 42
telemt_desync_total 1624
telemt_desync_full_logged_total 929
telemt_desync_suppressed_total 695
telemt_desync_frames_bucket_total{bucket="1_2"} 326
telemt_desync_frames_bucket_total{bucket="3_10"} 625
telemt_desync_frames_bucket_total{bucket="gt_10"} 673
telemt_pool_swap_total 12
telemt_pool_force_close_total 363
telemt_me_writer_close_signal_drop_total 32
telemt_me_draining_writers_reap_progress_total 3991
telemt_me_writer_removed_unexpected_total 114
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 339
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3760
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3628
telemt_me_writer_teardown_success_total{mode="normal"} 4099
telemt_me_writer_teardown_noop_total 3991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8084
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8090
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.110501
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8090
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 32
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 96
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 378934
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 6209970372 (5.78 GB)
telemt_user_octets_to_client{user="hello"} 113545593204 (105.75 GB)
telemt_user_unique_ips_current{user="hello"} 918
telemt_user_unique_ips_recent_window{user="hello"} 300
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 86569.3 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6889897
telemt_connections_bad_total 534175
telemt_connections_current 3919
telemt_connections_me_current 3919
telemt_handshake_timeouts_total 214685
telemt_upstream_connect_attempt_total 31108
telemt_upstream_connect_success_total 31046
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 31052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16934
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 126
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1345
telemt_me_reconnect_success_total 669
telemt_me_reader_eof_total 679
telemt_me_idle_close_by_peer_total 679
telemt_me_route_drop_no_conn_total 4357854
telemt_me_route_drop_channel_closed_total 64
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5639544
telemt_me_endpoint_quarantine_total 537
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 641
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
telemt_me_writers_active_current 43
telemt_desync_total 23294
telemt_desync_full_logged_total 7749
telemt_desync_suppressed_total 15545
telemt_desync_frames_bucket_total{bucket="1_2"} 4866
telemt_desync_frames_bucket_total{bucket="3_10"} 9269
telemt_desync_frames_bucket_total{bucket="gt_10"} 9159
telemt_pool_swap_total 93
telemt_pool_force_close_total 3094
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 502
telemt_me_draining_writers_reap_progress_total 28289
telemt_me_writer_removed_unexpected_total 653
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2429
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26144
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25195
telemt_me_writer_teardown_success_total{mode="normal"} 28573
telemt_me_writer_teardown_noop_total 28326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56899
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 137.929438
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56899
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 502
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 600
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 5632794
telemt_user_connections_current{user="hello"} 3919
telemt_user_octets_from_client{user="hello"} 97018758908 (90.36 GB)
telemt_user_octets_to_client{user="hello"} 1771024177200 (1.61 TB)
telemt_user_unique_ips_current{user="hello"} 1633
telemt_user_unique_ips_recent_window{user="hello"} 458
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 86570.7 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5577820
telemt_connections_bad_total 539749
telemt_connections_current 3002
telemt_connections_me_current 3002
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 183532
telemt_upstream_connect_attempt_total 35198
telemt_upstream_connect_success_total 34880
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 35044
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17644
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16668
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 541
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1669
telemt_me_reconnect_success_total 696
telemt_me_reader_eof_total 670
telemt_me_idle_close_by_peer_total 670
telemt_me_route_drop_no_conn_total 1931525
telemt_me_route_drop_channel_closed_total 221
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4175103
telemt_me_endpoint_quarantine_total 532
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 660
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
telemt_desync_total 19874
telemt_desync_full_logged_total 6573
telemt_desync_suppressed_total 13301
telemt_desync_frames_bucket_total{bucket="1_2"} 4871
telemt_desync_frames_bucket_total{bucket="3_10"} 7690
telemt_desync_frames_bucket_total{bucket="gt_10"} 7313
telemt_pool_swap_total 95
telemt_pool_force_close_total 2851
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 322
telemt_me_draining_writers_reap_progress_total 27064
telemt_me_writer_removed_unexpected_total 649
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2353
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25289
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2656
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 195
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24213
telemt_me_writer_teardown_success_total{mode="normal"} 27642
telemt_me_writer_teardown_noop_total 27069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 53122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 53621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54711
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.876099
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54711
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 322
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 596
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 4167818
telemt_user_connections_current{user="hello"} 3002
telemt_user_octets_from_client{user="hello"} 125459615973 (116.84 GB)
telemt_user_octets_to_client{user="hello"} 1908700628419 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1278
telemt_user_unique_ips_recent_window{user="hello"} 368
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 86534.5 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5506617
telemt_connections_bad_total 497483
telemt_connections_current 3060
telemt_connections_me_current 3060
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 167179
telemt_upstream_connect_attempt_total 41620
telemt_upstream_connect_success_total 41352
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 41487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18121
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1038
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1728
telemt_me_reconnect_success_total 762
telemt_me_reader_eof_total 706
telemt_me_idle_close_by_peer_total 706
telemt_me_route_drop_no_conn_total 1985558
telemt_me_route_drop_channel_closed_total 95
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4159259
telemt_me_endpoint_quarantine_total 583
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 644
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 19609
telemt_desync_full_logged_total 6399
telemt_desync_suppressed_total 13210
telemt_desync_frames_bucket_total{bucket="1_2"} 4887
telemt_desync_frames_bucket_total{bucket="3_10"} 7423
telemt_desync_frames_bucket_total{bucket="gt_10"} 7299
telemt_pool_swap_total 93
telemt_pool_force_close_total 2715
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 334
telemt_me_draining_writers_reap_progress_total 28483
telemt_me_writer_removed_unexpected_total 676
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2443
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26737
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2502
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25768
telemt_me_writer_teardown_success_total{mode="normal"} 29180
telemt_me_writer_teardown_noop_total 28493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57673
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 21.120015
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57673
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 334
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 658
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 4161406
telemt_user_connections_current{user="hello"} 3060
telemt_user_octets_from_client{user="hello"} 121589325035 (113.24 GB)
telemt_user_octets_to_client{user="hello"} 1901289517915 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1269
telemt_user_unique_ips_recent_window{user="hello"} 372
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 86574.0 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19082307
telemt_connections_bad_total 1231872
telemt_connections_current 3939
telemt_connections_me_current 3939
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 532264
telemt_upstream_connect_attempt_total 174772
telemt_upstream_connect_success_total 157872
telemt_upstream_connect_fail_total 15505
telemt_upstream_connect_attempts_per_request{bucket="1"} 173377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 112430
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35593
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8825
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15505
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 59436
telemt_me_reconnect_success_total 1805
telemt_me_reader_eof_total 1204
telemt_me_idle_close_by_peer_total 1203
telemt_me_route_drop_no_conn_total 39051163
telemt_me_route_drop_channel_closed_total 113
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15706796
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 640
telemt_me_single_endpoint_outage_enter_total 103
telemt_me_single_endpoint_outage_exit_total 103
telemt_me_single_endpoint_outage_reconnect_attempt_total 221
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 221
telemt_me_single_endpoint_shadow_rotate_total 674
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 52
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
telemt_me_writers_active_current 68
telemt_desync_total 29348
telemt_desync_full_logged_total 8647
telemt_desync_suppressed_total 20701
telemt_desync_frames_bucket_total{bucket="1_2"} 6427
telemt_desync_frames_bucket_total{bucket="3_10"} 13001
telemt_desync_frames_bucket_total{bucket="gt_10"} 9920
telemt_pool_swap_total 89
telemt_pool_force_close_total 2947
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 670
telemt_me_draining_writers_reap_progress_total 26655
telemt_me_writer_removed_unexpected_total 1669
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3567
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24501
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2485
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23708
telemt_me_writer_teardown_success_total{mode="normal"} 28068
telemt_me_writer_teardown_noop_total 26681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54749
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 202.967775
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54749
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 670
telemt_me_refill_failed_total 3519
telemt_me_writer_restored_same_endpoint_total 1260
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14223
telemt_me_writer_removed_unexpected_minus_restored_total 397
telemt_user_connections_total{user="hello"} 15826081
telemt_user_connections_current{user="hello"} 3939
telemt_user_octets_from_client{user="hello"} 150384240807 (140.06 GB)
telemt_user_octets_to_client{user="hello"} 966881492455 (900.48 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1482
telemt_user_unique_ips_recent_window{user="hello"} 538
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 86541.6 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5409153
telemt_connections_bad_total 522923
telemt_connections_current 3188
telemt_connections_me_current 3188
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 111559
telemt_upstream_connect_attempt_total 44731
telemt_upstream_connect_success_total 44244
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 44647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25535
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18382
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 326
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_reconnect_attempts_total 11068
telemt_me_reconnect_success_total 1268
telemt_me_reader_eof_total 1199
telemt_me_idle_close_by_peer_total 1199
telemt_me_route_drop_no_conn_total 2263170
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4197501
telemt_me_endpoint_quarantine_total 533
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 643
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
telemt_me_writers_active_current 46
telemt_desync_total 20792
telemt_desync_full_logged_total 7212
telemt_desync_suppressed_total 13580
telemt_desync_frames_bucket_total{bucket="1_2"} 3977
telemt_desync_frames_bucket_total{bucket="3_10"} 8109
telemt_desync_frames_bucket_total{bucket="gt_10"} 8706
telemt_pool_swap_total 88
telemt_pool_force_close_total 2577
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 317
telemt_me_draining_writers_reap_progress_total 29296
telemt_me_writer_removed_unexpected_total 1179
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2987
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27501
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2215
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26719
telemt_me_writer_teardown_success_total{mode="normal"} 30488
telemt_me_writer_teardown_noop_total 29297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59785
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.276369
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59785
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 317
telemt_me_refill_failed_total 591
telemt_me_writer_restored_same_endpoint_total 1074
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 1512
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 4187310
telemt_user_connections_current{user="hello"} 3188
telemt_user_octets_from_client{user="hello"} 111645281477 (103.98 GB)
telemt_user_octets_to_client{user="hello"} 1697494363695 (1.54 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1352
telemt_user_unique_ips_recent_window{user="hello"} 404
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 23377.2 (6h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3113321
telemt_connections_bad_total 115739
telemt_connections_current 3059
telemt_connections_me_current 3059
telemt_handshake_timeouts_total 1341302
telemt_upstream_connect_attempt_total 7553
telemt_upstream_connect_success_total 7451
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 7547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3300
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_reconnect_attempts_total 2199
telemt_me_reconnect_success_total 258
telemt_me_reader_eof_total 200
telemt_me_idle_close_by_peer_total 200
telemt_me_route_drop_no_conn_total 908085
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1475303
telemt_me_endpoint_quarantine_total 119
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 171
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
telemt_me_writers_active_current 43
telemt_desync_total 8099
telemt_desync_full_logged_total 2687
telemt_desync_suppressed_total 5412
telemt_desync_frames_bucket_total{bucket="1_2"} 1448
telemt_desync_frames_bucket_total{bucket="3_10"} 3068
telemt_desync_frames_bucket_total{bucket="gt_10"} 3583
telemt_pool_swap_total 24
telemt_pool_force_close_total 784
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 6573
telemt_me_writer_removed_unexpected_total 218
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 625
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6173
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 679
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 105
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5789
telemt_me_writer_teardown_success_total{mode="normal"} 6798
telemt_me_writer_teardown_noop_total 6573
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13371
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.047261
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13371
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 210
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 192
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1471036
telemt_user_connections_current{user="hello"} 3059
telemt_user_octets_from_client{user="hello"} 44226865232 (41.19 GB)
telemt_user_octets_to_client{user="hello"} 607374250644 (565.66 GB)
telemt_user_unique_ips_current{user="hello"} 1272
telemt_user_unique_ips_recent_window{user="hello"} 346
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 4348.0 (1h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48452
telemt_connections_bad_total 142
telemt_connections_current 557
telemt_connections_me_current 557
telemt_handshake_timeouts_total 781
telemt_upstream_connect_attempt_total 1875
telemt_upstream_connect_success_total 1869
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 1874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1093
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_reconnect_attempts_total 49
telemt_me_reconnect_success_total 19
telemt_me_reader_eof_total 19
telemt_me_idle_close_by_peer_total 19
telemt_me_route_drop_no_conn_total 14165
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43143
telemt_me_endpoint_quarantine_total 23
telemt_me_single_endpoint_shadow_rotate_total 39
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
telemt_me_writers_active_current 43
telemt_desync_total 313
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 220
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 4
telemt_pool_force_close_total 111
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 1615
telemt_me_writer_removed_unexpected_total 19
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 99
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1535
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 111
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1504
telemt_me_writer_teardown_success_total{mode="normal"} 1634
telemt_me_writer_teardown_noop_total 1615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 3248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 3249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 3249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 3249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 3249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 3249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 3249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 3249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 3249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 3249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 3249
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.207193
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 3249
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 16
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 43077
telemt_user_connections_current{user="hello"} 557
telemt_user_octets_from_client{user="hello"} 1033515816 (985.64 MB)
telemt_user_octets_to_client{user="hello"} 36127418900 (33.65 GB)
telemt_user_unique_ips_current{user="hello"} 232
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 86546.3 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6425570
telemt_connections_bad_total 659151
telemt_connections_current 3597
telemt_connections_me_current 3597
telemt_handshake_timeouts_total 185975
telemt_upstream_connect_attempt_total 32822
telemt_upstream_connect_success_total 32691
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 32785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16180
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16472
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_reconnect_attempts_total 1394
telemt_me_reconnect_success_total 701
telemt_me_reader_eof_total 676
telemt_me_idle_close_by_peer_total 676
telemt_me_route_drop_no_conn_total 1989703
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 22
telemt_me_route_drop_queue_full_profile_total{profile="high"} 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4924876
telemt_me_endpoint_quarantine_total 577
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 658
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
telemt_me_writers_active_current 45
telemt_desync_total 18764
telemt_desync_full_logged_total 6244
telemt_desync_suppressed_total 12520
telemt_desync_frames_bucket_total{bucket="1_2"} 4575
telemt_desync_frames_bucket_total{bucket="3_10"} 6842
telemt_desync_frames_bucket_total{bucket="gt_10"} 7347
telemt_pool_swap_total 96
telemt_pool_force_close_total 2596
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 328
telemt_me_draining_writers_reap_progress_total 29446
telemt_me_writer_removed_unexpected_total 659
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2398
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27714
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2512
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26850
telemt_me_writer_teardown_success_total{mode="normal"} 30112
telemt_me_writer_teardown_noop_total 29448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59560
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.623966
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59560
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 328
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 626
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 4900790
telemt_user_connections_current{user="hello"} 3597
telemt_user_octets_from_client{user="hello"} 97538969976 (90.84 GB)
telemt_user_octets_to_client{user="hello"} 2281309946404 (2.07 TB)
telemt_user_unique_ips_current{user="hello"} 1361
telemt_user_unique_ips_recent_window{user="hello"} 413
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 86542.4 (24h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5444757
telemt_connections_bad_total 508734
telemt_connections_current 3388
telemt_connections_me_current 3388
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 155762
telemt_upstream_connect_attempt_total 49272
telemt_upstream_connect_success_total 48907
telemt_upstream_connect_fail_total 306
telemt_upstream_connect_attempts_per_request{bucket="1"} 49213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29388
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18387
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 614
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 306
telemt_me_reconnect_attempts_total 4481
telemt_me_reconnect_success_total 992
telemt_me_reader_eof_total 877
telemt_me_idle_close_by_peer_total 877
telemt_me_seq_mismatch_total 38
telemt_me_route_drop_no_conn_total 2041467
telemt_me_route_drop_channel_closed_total 186
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4289860
telemt_me_endpoint_quarantine_total 688
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 656
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
telemt_me_writers_active_current 43
telemt_desync_total 17439
telemt_desync_full_logged_total 5874
telemt_desync_suppressed_total 11565
telemt_desync_frames_bucket_total{bucket="1_2"} 4319
telemt_desync_frames_bucket_total{bucket="3_10"} 6409
telemt_desync_frames_bucket_total{bucket="gt_10"} 6711
telemt_pool_swap_total 94
telemt_pool_force_close_total 2521
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 326
telemt_me_draining_writers_reap_progress_total 28715
telemt_me_writer_removed_unexpected_total 890
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2874
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26770
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2327
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 194
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26194
telemt_me_writer_teardown_success_total{mode="normal"} 29644
telemt_me_writer_teardown_noop_total 28717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58361
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.713448
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58361
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 326
telemt_me_refill_failed_total 199
telemt_me_writer_restored_same_endpoint_total 764
telemt_me_writer_restored_fallback_total 48
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 4294250
telemt_user_connections_current{user="hello"} 3388
telemt_user_octets_from_client{user="hello"} 82038868605 (76.40 GB)
telemt_user_octets_to_client{user="hello"} 1798276637304 (1.64 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1346
telemt_user_unique_ips_recent_window{user="hello"} 400
```