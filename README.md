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

# Server Metrics 2026-03-23 05:00:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 114813.2 (31h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3914309
telemt_connections_bad_total 386909
telemt_connections_current 1473
telemt_connections_me_current 1473
telemt_handshake_timeouts_total 132005
telemt_upstream_connect_attempt_total 42759
telemt_upstream_connect_success_total 42758
telemt_upstream_connect_attempts_per_request{bucket="1"} 42758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14847
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27772
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 451
telemt_me_reconnect_attempts_total 1470
telemt_me_reconnect_success_total 669
telemt_me_reader_eof_total 688
telemt_me_idle_close_by_peer_total 688
telemt_me_route_drop_no_conn_total 3051270
telemt_me_route_drop_channel_closed_total 1258
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3184936
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 899
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
telemt_desync_total 13659
telemt_desync_full_logged_total 4369
telemt_desync_suppressed_total 9290
telemt_desync_frames_bucket_total{bucket="1_2"} 3576
telemt_desync_frames_bucket_total{bucket="3_10"} 5031
telemt_desync_frames_bucket_total{bucket="gt_10"} 5052
telemt_pool_swap_total 127
telemt_pool_force_close_total 3881
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 699
telemt_me_draining_writers_reap_progress_total 39190
telemt_me_writer_removed_unexpected_total 663
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2798
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36670
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3816
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35309
telemt_me_writer_teardown_success_total{mode="normal"} 39468
telemt_me_writer_teardown_noop_total 39203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69267
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78671
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 389.656625
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78671
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 699
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 600
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 3173376
telemt_user_connections_current{user="hello"} 1473
telemt_user_octets_from_client{user="hello"} 44510640376 (41.45 GB)
telemt_user_octets_to_client{user="hello"} 871897729260 (812.02 GB)
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 128179.1 (35h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4120515
telemt_connections_bad_total 383536
telemt_connections_current 483
telemt_connections_me_current 483
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 105585
telemt_upstream_connect_attempt_total 80233
telemt_upstream_connect_success_total 79274
telemt_upstream_connect_fail_total 851
telemt_upstream_connect_attempts_per_request{bucket="1"} 80125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43845
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 851
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10818
telemt_me_reconnect_success_total 3878
telemt_me_reader_eof_total 3854
telemt_me_idle_close_by_peer_total 3854
telemt_me_route_drop_no_conn_total 3663141
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3269014
telemt_me_endpoint_quarantine_total 1048
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1010
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 13442
telemt_desync_full_logged_total 7573
telemt_desync_suppressed_total 5869
telemt_desync_frames_bucket_total{bucket="1_2"} 3061
telemt_desync_frames_bucket_total{bucket="3_10"} 5275
telemt_desync_frames_bucket_total{bucket="gt_10"} 5106
telemt_pool_swap_total 121
telemt_pool_force_close_total 3368
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 260
telemt_me_draining_writers_reap_progress_total 53771
telemt_me_writer_removed_unexpected_total 3775
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6814
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50773
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2886
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 482
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50403
telemt_me_writer_teardown_success_total{mode="normal"} 57587
telemt_me_writer_teardown_noop_total 53772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 110973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111359
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.830998
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111359
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 260
telemt_me_refill_failed_total 273
telemt_me_writer_restored_same_endpoint_total 3434
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 3283462
telemt_user_connections_current{user="hello"} 483
telemt_user_octets_from_client{user="hello"} 44226373103 (41.19 GB)
telemt_user_octets_to_client{user="hello"} 824157906057 (767.56 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 297
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 203038.9 (56h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16604009
telemt_connections_bad_total 1683355
telemt_connections_current 1396
telemt_connections_me_current 1396
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 405218
telemt_upstream_connect_attempt_total 91326
telemt_upstream_connect_success_total 91219
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 91236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1731
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3201
telemt_me_reconnect_success_total 1674
telemt_me_reader_eof_total 1631
telemt_me_idle_close_by_peer_total 1629
telemt_me_route_drop_no_conn_total 14098511
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13187032
telemt_me_endpoint_quarantine_total 1378
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1538
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 54925
telemt_desync_full_logged_total 17545
telemt_desync_suppressed_total 37380
telemt_desync_frames_bucket_total{bucket="1_2"} 12242
telemt_desync_frames_bucket_total{bucket="3_10"} 21509
telemt_desync_frames_bucket_total{bucket="gt_10"} 21174
telemt_pool_swap_total 220
telemt_pool_force_close_total 7070
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1096
telemt_me_draining_writers_reap_progress_total 70224
telemt_me_writer_removed_unexpected_total 1565
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5898
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65176
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63154
telemt_me_writer_teardown_success_total{mode="normal"} 71074
telemt_me_writer_teardown_noop_total 70278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 129991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138024
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141343
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141352
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.839385
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141352
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1096
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1452
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 13186904
telemt_user_connections_current{user="hello"} 1396
telemt_user_octets_from_client{user="hello"} 199680525673 (185.97 GB)
telemt_user_octets_to_client{user="hello"} 3574266560927 (3.25 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 612
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 203040.3 (56h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12125683
telemt_connections_bad_total 1284641
telemt_connections_current 1056
telemt_connections_me_current 1056
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 350855
telemt_upstream_connect_attempt_total 105687
telemt_upstream_connect_success_total 104275
telemt_upstream_connect_fail_total 899
telemt_upstream_connect_attempts_per_request{bucket="1"} 105174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44960
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 899
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4648
telemt_me_reconnect_success_total 1998
telemt_me_reader_eof_total 1857
telemt_me_idle_close_by_peer_total 1857
telemt_me_route_drop_no_conn_total 4600635
telemt_me_route_drop_channel_closed_total 503
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8971793
telemt_me_endpoint_quarantine_total 1388
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1555
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
telemt_me_writers_active_current 43
telemt_desync_total 39413
telemt_desync_full_logged_total 13280
telemt_desync_suppressed_total 26133
telemt_desync_frames_bucket_total{bucket="1_2"} 9773
telemt_desync_frames_bucket_total{bucket="3_10"} 15149
telemt_desync_frames_bucket_total{bucket="gt_10"} 14491
telemt_pool_swap_total 217
telemt_pool_force_close_total 6416
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 718
telemt_me_draining_writers_reap_progress_total 68308
telemt_me_writer_removed_unexpected_total 1889
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5984
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64074
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61892
telemt_me_writer_teardown_success_total{mode="normal"} 70058
telemt_me_writer_teardown_noop_total 68333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 134867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 137966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138391
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.610889
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138391
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 718
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1704
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 8909385
telemt_user_connections_current{user="hello"} 1056
telemt_user_octets_from_client{user="hello"} 219439081400 (204.37 GB)
telemt_user_octets_to_client{user="hello"} 4016121950723 (3.65 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 420
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 203004.3 (56h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11275530
telemt_connections_bad_total 1032128
telemt_connections_current 894
telemt_connections_me_current 894
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 353084
telemt_upstream_connect_attempt_total 90076
telemt_upstream_connect_success_total 88502
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 88707
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40548
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43520
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5878
telemt_me_reconnect_success_total 2466
telemt_me_reader_eof_total 2212
telemt_me_idle_close_by_peer_total 2211
telemt_me_route_drop_no_conn_total 5369168
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8482329
telemt_me_endpoint_quarantine_total 1437
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1516
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 72
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
telemt_desync_total 38584
telemt_desync_full_logged_total 12804
telemt_desync_suppressed_total 25780
telemt_desync_frames_bucket_total{bucket="1_2"} 9746
telemt_desync_frames_bucket_total{bucket="3_10"} 14773
telemt_desync_frames_bucket_total{bucket="gt_10"} 14065
telemt_pool_swap_total 213
telemt_pool_force_close_total 6302
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 761
telemt_me_draining_writers_reap_progress_total 68884
telemt_me_writer_removed_unexpected_total 2358
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6724
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64454
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62582
telemt_me_writer_teardown_success_total{mode="normal"} 71178
telemt_me_writer_teardown_noop_total 68955
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137978
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 139866
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 139994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140133
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.955010
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140133
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 761
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2147
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8474188
telemt_user_connections_current{user="hello"} 894
telemt_user_octets_from_client{user="hello"} 193866012539 (180.55 GB)
telemt_user_octets_to_client{user="hello"} 3516991445597 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 367
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 73299.5 (20h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11577551
telemt_connections_bad_total 681425
telemt_connections_current 1704
telemt_connections_me_current 1704
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 309278
telemt_upstream_connect_attempt_total 65386
telemt_upstream_connect_success_total 61943
telemt_upstream_connect_fail_total 2217
telemt_upstream_connect_attempts_per_request{bucket="1"} 64160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22530
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6036
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2217
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8293
telemt_me_reconnect_success_total 1484
telemt_me_reader_eof_total 953
telemt_me_idle_close_by_peer_total 952
telemt_me_route_drop_no_conn_total 25354516
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9590401
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 103
telemt_me_single_endpoint_outage_exit_total 103
telemt_me_single_endpoint_outage_reconnect_attempt_total 201
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 201
telemt_me_single_endpoint_shadow_rotate_total 591
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
telemt_me_writers_active_current 45
telemt_desync_total 17138
telemt_desync_full_logged_total 4754
telemt_desync_suppressed_total 12384
telemt_desync_frames_bucket_total{bucket="1_2"} 3310
telemt_desync_frames_bucket_total{bucket="3_10"} 7006
telemt_desync_frames_bucket_total{bucket="gt_10"} 6822
telemt_pool_swap_total 76
telemt_pool_force_close_total 2368
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 523
telemt_me_draining_writers_reap_progress_total 24305
telemt_me_writer_removed_unexpected_total 1346
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3110
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22493
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 326
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21937
telemt_me_writer_teardown_success_total{mode="normal"} 25603
telemt_me_writer_teardown_noop_total 24324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49748
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49927
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.807301
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49927
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 523
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 958
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 9616750
telemt_user_connections_current{user="hello"} 1704
telemt_user_octets_from_client{user="hello"} 90242495874 (84.04 GB)
telemt_user_octets_to_client{user="hello"} 701714198081 (653.52 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 652
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 203011.1 (56h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11233553
telemt_connections_bad_total 990438
telemt_connections_current 1305
telemt_connections_me_current 1305
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 249394
telemt_upstream_connect_attempt_total 119025
telemt_upstream_connect_success_total 117789
telemt_upstream_connect_fail_total 1059
telemt_upstream_connect_attempts_per_request{bucket="1"} 118848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69141
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47034
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1059
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73517
telemt_me_reconnect_success_total 3249
telemt_me_reader_eof_total 2945
telemt_me_idle_close_by_peer_total 2942
telemt_me_route_drop_no_conn_total 5307272
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8843667
telemt_me_endpoint_quarantine_total 1380
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1546
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
telemt_me_writers_active_current 43
telemt_desync_total 47111
telemt_desync_full_logged_total 16197
telemt_desync_suppressed_total 30914
telemt_desync_frames_bucket_total{bucket="1_2"} 9562
telemt_desync_frames_bucket_total{bucket="3_10"} 18073
telemt_desync_frames_bucket_total{bucket="gt_10"} 19476
telemt_pool_swap_total 209
telemt_pool_force_close_total 6029
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 72952
telemt_me_writer_removed_unexpected_total 2962
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7280
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68681
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5280
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 66923
telemt_me_writer_teardown_success_total{mode="normal"} 75961
telemt_me_writer_teardown_noop_total 72953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 148597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 148870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 148904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 148907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 148907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 148910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 148914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 148914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 148914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 148914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 148914
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.356839
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 148914
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 4322
telemt_me_writer_restored_same_endpoint_total 2736
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8846367
telemt_user_connections_current{user="hello"} 1305
telemt_user_octets_from_client{user="hello"} 198643840737 (185.00 GB)
telemt_user_octets_to_client{user="hello"} 3382118556260 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 139847.3 (38h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11998964
telemt_connections_bad_total 492670
telemt_connections_current 1023
telemt_connections_me_current 1023
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4842247
telemt_upstream_connect_attempt_total 67951
telemt_upstream_connect_success_total 67465
telemt_upstream_connect_fail_total 473
telemt_upstream_connect_attempts_per_request{bucket="1"} 67938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35546
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 473
telemt_me_reconnect_attempts_total 49310
telemt_me_reconnect_success_total 1951
telemt_me_reader_eof_total 1633
telemt_me_idle_close_by_peer_total 1632
telemt_me_route_drop_no_conn_total 4131617
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5766598
telemt_me_endpoint_quarantine_total 969
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1080
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
telemt_me_writers_active_current 42
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32434
telemt_desync_full_logged_total 11081
telemt_desync_suppressed_total 21353
telemt_desync_frames_bucket_total{bucket="1_2"} 6509
telemt_desync_frames_bucket_total{bucket="3_10"} 12779
telemt_desync_frames_bucket_total{bucket="gt_10"} 13146
telemt_pool_swap_total 149
telemt_pool_force_close_total 4221
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 52856
telemt_me_writer_removed_unexpected_total 1673
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4183
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50400
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3777
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48635
telemt_me_writer_teardown_success_total{mode="normal"} 54583
telemt_me_writer_teardown_noop_total 52863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107446
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.809849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107446
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 2751
telemt_me_writer_restored_same_endpoint_total 1724
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5758547
telemt_user_connections_current{user="hello"} 1023
telemt_user_octets_from_client{user="hello"} 121453164568 (113.11 GB)
telemt_user_octets_to_client{user="hello"} 2242522756002 (2.04 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 158
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 120817.8 (33h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1661828
telemt_connections_bad_total 37237
telemt_connections_current 658
telemt_connections_me_current 658
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 34759
telemt_upstream_connect_attempt_total 57053
telemt_upstream_connect_success_total 56874
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 57025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26906
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29135
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 833
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2499
telemt_me_reconnect_success_total 1005
telemt_me_reader_eof_total 1001
telemt_me_idle_close_by_peer_total 1001
telemt_me_route_drop_no_conn_total 554579
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1477362
telemt_me_endpoint_quarantine_total 1027
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 997
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
telemt_me_writers_active_current 43
telemt_desync_total 10245
telemt_desync_full_logged_total 2891
telemt_desync_suppressed_total 7354
telemt_desync_frames_bucket_total{bucket="1_2"} 3229
telemt_desync_frames_bucket_total{bucket="3_10"} 3853
telemt_desync_frames_bucket_total{bucket="gt_10"} 3163
telemt_pool_swap_total 131
telemt_pool_force_close_total 3302
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 177
telemt_me_draining_writers_reap_progress_total 48635
telemt_me_writer_removed_unexpected_total 964
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3675
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45968
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3214
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45333
telemt_me_writer_teardown_success_total{mode="normal"} 49643
telemt_me_writer_teardown_noop_total 48639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98282
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.667070
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98282
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 177
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 860
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1472964
telemt_user_connections_current{user="hello"} 658
telemt_user_octets_from_client{user="hello"} 27320869909 (25.44 GB)
telemt_user_octets_to_client{user="hello"} 608955687651 (567.13 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 276
telemt_user_unique_ips_recent_window{user="hello"} 257
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 203015.6 (56h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13521691
telemt_connections_bad_total 1632579
telemt_connections_current 1175
telemt_connections_me_current 1175
telemt_handshake_timeouts_total 396136
telemt_upstream_connect_attempt_total 81837
telemt_upstream_connect_success_total 81474
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 81700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40314
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41055
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3214
telemt_me_reconnect_success_total 1611
telemt_me_reader_eof_total 1602
telemt_me_idle_close_by_peer_total 1602
telemt_me_route_drop_no_conn_total 4518772
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10194305
telemt_me_endpoint_quarantine_total 1502
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1543
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
telemt_me_writers_active_current 46
telemt_desync_total 42780
telemt_desync_full_logged_total 13962
telemt_desync_suppressed_total 28818
telemt_desync_frames_bucket_total{bucket="1_2"} 10422
telemt_desync_frames_bucket_total{bucket="3_10"} 15702
telemt_desync_frames_bucket_total{bucket="gt_10"} 16656
telemt_pool_swap_total 225
telemt_pool_force_close_total 5874
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 699
telemt_me_draining_writers_reap_progress_total 74089
telemt_me_writer_removed_unexpected_total 1532
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5704
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69977
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68215
telemt_me_writer_teardown_success_total{mode="normal"} 75681
telemt_me_writer_teardown_noop_total 74091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 149639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149772
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.979170
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149772
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 699
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 1418
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 10160762
telemt_user_connections_current{user="hello"} 1175
telemt_user_octets_from_client{user="hello"} 196562757196 (183.06 GB)
telemt_user_octets_to_client{user="hello"} 4528548233172 (4.12 TB)
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 203012.2 (56h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11839728
telemt_connections_bad_total 1386535
telemt_connections_current 1218
telemt_connections_me_current 1218
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 318645
telemt_upstream_connect_attempt_total 109670
telemt_upstream_connect_success_total 108725
telemt_upstream_connect_fail_total 736
telemt_upstream_connect_attempts_per_request{bucket="1"} 109461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59034
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 736
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11064
telemt_me_reconnect_success_total 2749
telemt_me_reader_eof_total 2552
telemt_me_idle_close_by_peer_total 2551
telemt_me_seq_mismatch_total 107
telemt_me_route_drop_no_conn_total 5685899
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9113133
telemt_me_endpoint_quarantine_total 1676
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1548
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
telemt_me_writers_active_current 42
telemt_desync_total 42422
telemt_desync_full_logged_total 13657
telemt_desync_suppressed_total 28765
telemt_desync_frames_bucket_total{bucket="1_2"} 11031
telemt_desync_frames_bucket_total{bucket="3_10"} 15569
telemt_desync_frames_bucket_total{bucket="gt_10"} 15822
telemt_pool_swap_total 215
telemt_pool_force_close_total 5637
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 74416
telemt_me_writer_removed_unexpected_total 2588
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7106
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69998
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5166
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68779
telemt_me_writer_teardown_success_total{mode="normal"} 77104
telemt_me_writer_teardown_noop_total 74421
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 151156
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151525
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.672283
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151525
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 432
telemt_me_writer_restored_same_endpoint_total 2191
telemt_me_writer_restored_fallback_total 142
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 9117588
telemt_user_connections_current{user="hello"} 1218
telemt_user_octets_from_client{user="hello"} 158988184164 (148.07 GB)
telemt_user_octets_to_client{user="hello"} 3569611833698 (3.25 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 479
telemt_user_unique_ips_recent_window{user="hello"} 153
```