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

# Server Metrics 2026-03-21 22:51:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 6326.1 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 110882
telemt_connections_bad_total 8068
telemt_connections_current 758
telemt_connections_me_current 758
telemt_handshake_timeouts_total 5229
telemt_upstream_connect_attempt_total 2431
telemt_upstream_connect_success_total 2430
telemt_upstream_connect_attempts_per_request{bucket="1"} 2430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1538
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_reconnect_attempts_total 51
telemt_me_reconnect_success_total 32
telemt_me_reader_eof_total 33
telemt_me_idle_close_by_peer_total 33
telemt_me_route_drop_no_conn_total 22913
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 90154
telemt_me_endpoint_quarantine_total 35
telemt_me_single_endpoint_shadow_rotate_total 53
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_warm_current 5
telemt_desync_total 586
telemt_desync_full_logged_total 184
telemt_desync_suppressed_total 402
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 284
telemt_pool_swap_total 6
telemt_pool_force_close_total 161
telemt_me_writer_close_signal_drop_total 13
telemt_me_draining_writers_reap_progress_total 2126
telemt_me_writer_removed_unexpected_total 31
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 153
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2006
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1965
telemt_me_writer_teardown_success_total{mode="normal"} 2159
telemt_me_writer_teardown_noop_total 2126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4132
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4285
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.464729
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4285
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 13
telemt_me_refill_failed_total 1
telemt_me_writer_restored_same_endpoint_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 90074
telemt_user_connections_current{user="hello"} 758
telemt_user_octets_from_client{user="hello"} 1185265184 (1.10 GB)
telemt_user_octets_to_client{user="hello"} 33633127108 (31.32 GB)
telemt_user_unique_ips_current{user="hello"} 318
telemt_user_unique_ips_recent_window{user="hello"} 78
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 19692.4 (5h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 622183
telemt_connections_bad_total 28181
telemt_connections_current 629
telemt_connections_me_current 629
telemt_handshake_timeouts_total 23077
telemt_upstream_connect_attempt_total 8130
telemt_upstream_connect_success_total 7984
telemt_upstream_connect_fail_total 131
telemt_upstream_connect_attempts_per_request{bucket="1"} 8115
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4385
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 131
telemt_me_reconnect_attempts_total 649
telemt_me_reconnect_success_total 246
telemt_me_reader_eof_total 205
telemt_me_idle_close_by_peer_total 205
telemt_me_route_drop_no_conn_total 317103
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 507767
telemt_me_endpoint_quarantine_total 161
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 157
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_me_writers_active_current 48
telemt_desync_total 2256
telemt_desync_full_logged_total 1285
telemt_desync_suppressed_total 971
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 852
telemt_desync_frames_bucket_total{bucket="gt_10"} 932
telemt_pool_swap_total 21
telemt_pool_force_close_total 601
telemt_me_writer_close_signal_drop_total 47
telemt_me_draining_writers_reap_progress_total 7146
telemt_me_writer_removed_unexpected_total 194
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 617
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6721
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6545
telemt_me_writer_teardown_success_total{mode="normal"} 7338
telemt_me_writer_teardown_noop_total 7146
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14484
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.189691
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14484
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 47
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 171
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 507105
telemt_user_connections_current{user="hello"} 629
telemt_user_octets_from_client{user="hello"} 8636696740 (8.04 GB)
telemt_user_octets_to_client{user="hello"} 174051802968 (162.10 GB)
telemt_user_unique_ips_current{user="hello"} 441
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 94552.3 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7300771
telemt_connections_bad_total 558334
telemt_connections_current 2249
telemt_connections_me_current 2249
telemt_handshake_timeouts_total 232131
telemt_upstream_connect_attempt_total 34085
telemt_upstream_connect_success_total 34017
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 34024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15354
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18505
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1465
telemt_me_reconnect_success_total 719
telemt_me_reader_eof_total 728
telemt_me_idle_close_by_peer_total 728
telemt_me_route_drop_no_conn_total 4475425
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5974483
telemt_me_endpoint_quarantine_total 596
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 698
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
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 17
telemt_desync_total 25335
telemt_desync_full_logged_total 8347
telemt_desync_suppressed_total 16988
telemt_desync_frames_bucket_total{bucket="1_2"} 5440
telemt_desync_frames_bucket_total{bucket="3_10"} 9902
telemt_desync_frames_bucket_total{bucket="gt_10"} 9993
telemt_pool_swap_total 101
telemt_pool_force_close_total 3419
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 558
telemt_me_draining_writers_reap_progress_total 31030
telemt_me_writer_removed_unexpected_total 700
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2646
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28661
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3180
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27611
telemt_me_writer_teardown_success_total{mode="normal"} 31307
telemt_me_writer_teardown_noop_total 31074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62381
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.319841
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62381
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 558
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 642
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 5967195
telemt_user_connections_current{user="hello"} 2249
telemt_user_octets_from_client{user="hello"} 102489290396 (95.45 GB)
telemt_user_octets_to_client{user="hello"} 1940520226156 (1.76 TB)
telemt_user_unique_ips_current{user="hello"} 1035
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 94553.7 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5999986
telemt_connections_bad_total 575432
telemt_connections_current 1831
telemt_connections_me_current 1831
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 196804
telemt_upstream_connect_attempt_total 38007
telemt_upstream_connect_success_total 37672
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 37847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18945
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18157
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 543
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1743
telemt_me_reconnect_success_total 745
telemt_me_reader_eof_total 721
telemt_me_idle_close_by_peer_total 721
telemt_me_route_drop_no_conn_total 2113986
telemt_me_route_drop_channel_closed_total 242
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4487263
telemt_me_endpoint_quarantine_total 573
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 720
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
telemt_me_writers_warm_current 13
telemt_desync_total 21610
telemt_desync_full_logged_total 7247
telemt_desync_suppressed_total 14363
telemt_desync_frames_bucket_total{bucket="1_2"} 5224
telemt_desync_frames_bucket_total{bucket="3_10"} 8368
telemt_desync_frames_bucket_total{bucket="gt_10"} 8018
telemt_pool_swap_total 103
telemt_pool_force_close_total 3115
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 341
telemt_me_draining_writers_reap_progress_total 29593
telemt_me_writer_removed_unexpected_total 697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2536
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27687
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26478
telemt_me_writer_teardown_success_total{mode="normal"} 30223
telemt_me_writer_teardown_noop_total 29599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59822
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.810057
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59822
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 341
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 643
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 4445794
telemt_user_connections_current{user="hello"} 1831
telemt_user_octets_from_client{user="hello"} 136892702073 (127.49 GB)
telemt_user_octets_to_client{user="hello"} 2072933239215 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 847
telemt_user_unique_ips_recent_window{user="hello"} 195
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 94517.7 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5920598
telemt_connections_bad_total 534346
telemt_connections_current 1667
telemt_connections_me_current 1667
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 187748
telemt_upstream_connect_attempt_total 44393
telemt_upstream_connect_success_total 44096
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 44231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19595
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1045
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1787
telemt_me_reconnect_success_total 804
telemt_me_reader_eof_total 751
telemt_me_idle_close_by_peer_total 751
telemt_me_route_drop_no_conn_total 2080632
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4426376
telemt_me_endpoint_quarantine_total 631
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 703
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 21464
telemt_desync_full_logged_total 7077
telemt_desync_suppressed_total 14387
telemt_desync_frames_bucket_total{bucket="1_2"} 5289
telemt_desync_frames_bucket_total{bucket="3_10"} 8164
telemt_desync_frames_bucket_total{bucket="gt_10"} 8011
telemt_pool_swap_total 101
telemt_pool_force_close_total 2994
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 362
telemt_me_draining_writers_reap_progress_total 31003
telemt_me_writer_removed_unexpected_total 719
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2616
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29112
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28009
telemt_me_writer_teardown_success_total{mode="normal"} 31728
telemt_me_writer_teardown_noop_total 31014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 62742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 62742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 62742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 62742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 62742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 62742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 62742
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.120057
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 62742
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 362
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 695
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4427940
telemt_user_connections_current{user="hello"} 1667
telemt_user_octets_from_client{user="hello"} 130039489555 (121.11 GB)
telemt_user_octets_to_client{user="hello"} 2026637116599 (1.84 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 797
telemt_user_unique_ips_recent_window{user="hello"} 163
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 94557.0 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19751371
telemt_connections_bad_total 1406981
telemt_connections_current 2410
telemt_connections_me_current 2410
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 564122
telemt_upstream_connect_attempt_total 184146
telemt_upstream_connect_success_total 166805
telemt_upstream_connect_fail_total 15829
telemt_upstream_connect_attempts_per_request{bucket="1"} 182634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 118383
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 38408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1155
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8859
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15829
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 63995
telemt_me_reconnect_success_total 2026
telemt_me_reader_eof_total 1297
telemt_me_idle_close_by_peer_total 1296
telemt_me_route_drop_no_conn_total 39418973
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16134408
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 704
telemt_me_single_endpoint_outage_enter_total 113
telemt_me_single_endpoint_outage_exit_total 113
telemt_me_single_endpoint_outage_reconnect_attempt_total 241
telemt_me_single_endpoint_outage_reconnect_success_total 55
telemt_me_single_endpoint_quarantine_bypass_total 241
telemt_me_single_endpoint_shadow_rotate_total 733
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
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
telemt_me_writers_active_current 52
telemt_me_writers_warm_current 17
telemt_desync_total 31008
telemt_desync_full_logged_total 9190
telemt_desync_suppressed_total 21818
telemt_desync_frames_bucket_total{bucket="1_2"} 6786
telemt_desync_frames_bucket_total{bucket="3_10"} 13734
telemt_desync_frames_bucket_total{bucket="gt_10"} 10488
telemt_pool_swap_total 96
telemt_pool_force_close_total 3236
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 728
telemt_me_draining_writers_reap_progress_total 29259
telemt_me_writer_removed_unexpected_total 1891
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3968
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26909
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2723
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 513
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26023
telemt_me_writer_teardown_success_total{mode="normal"} 30877
telemt_me_writer_teardown_noop_total 29285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59730
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60157
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60162
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 209.118648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60162
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 728
telemt_me_refill_failed_total 3781
telemt_me_writer_restored_same_endpoint_total 1420
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14670
telemt_me_writer_removed_unexpected_minus_restored_total 452
telemt_user_connections_total{user="hello"} 16259212
telemt_user_connections_current{user="hello"} 2410
telemt_user_octets_from_client{user="hello"} 176150728038 (164.05 GB)
telemt_user_octets_to_client{user="hello"} 1072843354650 (999.16 GB)
telemt_user_msgs_from_client{user="hello"} 361669
telemt_user_msgs_to_client{user="hello"} 643484
telemt_user_unique_ips_current{user="hello"} 1114
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 94524.6 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5732468
telemt_connections_bad_total 535498
telemt_connections_current 1457
telemt_connections_me_current 1457
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 118529
telemt_upstream_connect_attempt_total 51971
telemt_upstream_connect_success_total 51402
telemt_upstream_connect_fail_total 483
telemt_upstream_connect_attempts_per_request{bucket="1"} 51885
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 483
telemt_me_reconnect_attempts_total 30714
telemt_me_reconnect_success_total 1403
telemt_me_reader_eof_total 1268
telemt_me_idle_close_by_peer_total 1268
telemt_me_route_drop_no_conn_total 2339782
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4468706
telemt_me_endpoint_quarantine_total 594
telemt_me_single_endpoint_outage_enter_total 17
telemt_me_single_endpoint_outage_exit_total 17
telemt_me_single_endpoint_outage_reconnect_attempt_total 17
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 17
telemt_me_single_endpoint_shadow_rotate_total 706
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 64
telemt_desync_total 22598
telemt_desync_full_logged_total 7868
telemt_desync_suppressed_total 14730
telemt_desync_frames_bucket_total{bucket="1_2"} 4292
telemt_desync_frames_bucket_total{bucket="3_10"} 8767
telemt_desync_frames_bucket_total{bucket="gt_10"} 9539
telemt_pool_swap_total 96
telemt_pool_force_close_total 2812
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 364
telemt_me_draining_writers_reap_progress_total 32041
telemt_me_writer_removed_unexpected_total 1292
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3286
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30062
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2444
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 368
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29229
telemt_me_writer_teardown_success_total{mode="normal"} 33348
telemt_me_writer_teardown_noop_total 32042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65387
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65390
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.654014
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65390
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 364
telemt_me_refill_failed_total 1804
telemt_me_writer_restored_same_endpoint_total 1169
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 3633
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 4461735
telemt_user_connections_current{user="hello"} 1457
telemt_user_octets_from_client{user="hello"} 119946776272 (111.71 GB)
telemt_user_octets_to_client{user="hello"} 1815329472330 (1.65 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 753
telemt_user_unique_ips_recent_window{user="hello"} 191
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 31360.4 (8h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3591870
telemt_connections_bad_total 127022
telemt_connections_current 1864
telemt_connections_me_current 1864
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1514398
telemt_upstream_connect_attempt_total 16156
telemt_upstream_connect_success_total 16028
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 16150
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6083
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_reconnect_attempts_total 31215
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 389
telemt_me_idle_close_by_peer_total 389
telemt_me_route_drop_no_conn_total 980342
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1719565
telemt_me_endpoint_quarantine_total 195
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 234
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 93
telemt_me_floor_cap_block_total 13
telemt_me_floor_swap_idle_failed_total 13
telemt_desync_total 9574
telemt_desync_full_logged_total 3227
telemt_desync_suppressed_total 6347
telemt_desync_frames_bucket_total{bucket="1_2"} 1702
telemt_desync_frames_bucket_total{bucket="3_10"} 3654
telemt_desync_frames_bucket_total{bucket="gt_10"} 4218
telemt_pool_swap_total 33
telemt_pool_force_close_total 1080
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 9742
telemt_me_writer_removed_unexpected_total 444
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1010
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9191
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 931
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 149
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8662
telemt_me_writer_teardown_success_total{mode="normal"} 10201
telemt_me_writer_teardown_noop_total 9743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 19551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 19786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19944
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.738652
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19944
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 1776
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 160
telemt_me_async_recovery_trigger_total 3121
telemt_user_connections_total{user="hello"} 1719496
telemt_user_connections_current{user="hello"} 1864
telemt_user_octets_from_client{user="hello"} 49688786120 (46.28 GB)
telemt_user_octets_to_client{user="hello"} 740567612542 (689.71 GB)
telemt_user_msgs_from_client{user="hello"} 43112
telemt_user_msgs_to_client{user="hello"} 113951
telemt_user_unique_ips_current{user="hello"} 947
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 12331.3 (3h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139575
telemt_connections_bad_total 1356
telemt_connections_current 374
telemt_connections_me_current 374
telemt_handshake_timeouts_total 3434
telemt_upstream_connect_attempt_total 5451
telemt_upstream_connect_success_total 5435
telemt_upstream_connect_fail_total 15
telemt_upstream_connect_attempts_per_request{bucket="1"} 5450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 118
telemt_me_reconnect_success_total 72
telemt_me_reader_eof_total 73
telemt_me_idle_close_by_peer_total 73
telemt_me_route_drop_no_conn_total 39660
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121312
telemt_me_endpoint_quarantine_total 100
telemt_me_single_endpoint_shadow_rotate_total 109
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
telemt_me_writers_active_current 48
telemt_desync_total 945
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 710
telemt_desync_frames_bucket_total{bucket="1_2"} 383
telemt_desync_frames_bucket_total{bucket="3_10"} 344
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 13
telemt_pool_force_close_total 321
telemt_me_writer_close_signal_drop_total 15
telemt_me_draining_writers_reap_progress_total 4813
telemt_me_writer_removed_unexpected_total 71
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 315
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4571
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4492
telemt_me_writer_teardown_success_total{mode="normal"} 4886
telemt_me_writer_teardown_noop_total 4813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9699
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.621178
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9699
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 15
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 66
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 121133
telemt_user_connections_current{user="hello"} 374
telemt_user_octets_from_client{user="hello"} 2289957124 (2.13 GB)
telemt_user_octets_to_client{user="hello"} 74392709400 (69.28 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 94528.9 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6861834
telemt_connections_bad_total 695587
telemt_connections_current 2172
telemt_connections_me_current 2172
telemt_handshake_timeouts_total 195276
telemt_upstream_connect_attempt_total 35837
telemt_upstream_connect_success_total 35695
telemt_upstream_connect_fail_total 105
telemt_upstream_connect_attempts_per_request{bucket="1"} 35800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17709
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 105
telemt_me_reconnect_attempts_total 1448
telemt_me_reconnect_success_total 751
telemt_me_reader_eof_total 730
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 2076527
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5222572
telemt_me_endpoint_quarantine_total 626
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 721
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
telemt_me_writers_active_current 47
telemt_desync_total 20039
telemt_desync_full_logged_total 6702
telemt_desync_suppressed_total 13337
telemt_desync_frames_bucket_total{bucket="1_2"} 4866
telemt_desync_frames_bucket_total{bucket="3_10"} 7298
telemt_desync_frames_bucket_total{bucket="gt_10"} 7875
telemt_pool_swap_total 104
telemt_pool_force_close_total 2850
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 32206
telemt_me_writer_removed_unexpected_total 707
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2615
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30311
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2762
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29356
telemt_me_writer_teardown_success_total{mode="normal"} 32926
telemt_me_writer_teardown_noop_total 32208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.466537
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 673
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 5197964
telemt_user_connections_current{user="hello"} 2172
telemt_user_octets_from_client{user="hello"} 104614694304 (97.43 GB)
telemt_user_octets_to_client{user="hello"} 2445541994356 (2.22 TB)
telemt_user_unique_ips_current{user="hello"} 899
telemt_user_unique_ips_recent_window{user="hello"} 190
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 94525.6 (26h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5866148
telemt_connections_bad_total 558089
telemt_connections_current 1906
telemt_connections_me_current 1906
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 164677
telemt_upstream_connect_attempt_total 51957
telemt_upstream_connect_success_total 51562
telemt_upstream_connect_fail_total 335
telemt_upstream_connect_attempts_per_request{bucket="1"} 51897
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30711
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 335
telemt_me_reconnect_attempts_total 5233
telemt_me_reconnect_success_total 1056
telemt_me_reader_eof_total 932
telemt_me_idle_close_by_peer_total 932
telemt_me_seq_mismatch_total 39
telemt_me_route_drop_no_conn_total 2128431
telemt_me_route_drop_channel_closed_total 188
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4591542
telemt_me_endpoint_quarantine_total 734
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 717
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 18818
telemt_desync_full_logged_total 6342
telemt_desync_suppressed_total 12476
telemt_desync_frames_bucket_total{bucket="1_2"} 4672
telemt_desync_frames_bucket_total{bucket="3_10"} 6857
telemt_desync_frames_bucket_total{bucket="gt_10"} 7289
telemt_pool_swap_total 102
telemt_pool_force_close_total 2807
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 31140
telemt_me_writer_removed_unexpected_total 943
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3099
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29027
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2584
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28333
telemt_me_writer_teardown_success_total{mode="normal"} 32126
telemt_me_writer_teardown_noop_total 31144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 61717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63037
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63232
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63270
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.553536
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63270
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 241
telemt_me_writer_restored_same_endpoint_total 818
telemt_me_writer_restored_fallback_total 50
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 75
telemt_user_connections_total{user="hello"} 4595019
telemt_user_connections_current{user="hello"} 1906
telemt_user_octets_from_client{user="hello"} 87829019873 (81.80 GB)
telemt_user_octets_to_client{user="hello"} 1974727595244 (1.80 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 845
telemt_user_unique_ips_recent_window{user="hello"} 189
```