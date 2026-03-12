# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
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

## rdp-onedash.ru
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

# Server Metrics 2026-03-12 18:21:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 38858.0 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199143
telemt_connections_bad_total 2415
telemt_handshake_timeouts_total 4948
telemt_upstream_connect_attempt_total 9835
telemt_upstream_connect_success_total 9792
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 9835
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5411
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1415
telemt_me_reconnect_attempts_total 11227
telemt_me_reconnect_success_total 7770
telemt_me_reader_eof_total 8231
telemt_me_idle_close_by_peer_total 8230
telemt_me_route_drop_no_conn_total 59388
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168061
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 633
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 395
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 240
telemt_desync_frames_bucket_total{bucket="gt_10"} 273
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 7969
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 7754
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 168020
telemt_user_connections_current{user="hello"} 266
telemt_user_octets_from_client{user="hello"} 2974875272 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 70940322012 (66.07 GB)
telemt_user_unique_ips_current{user="hello"} 79
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 38751.2 (10h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86153
telemt_connections_bad_total 472
telemt_handshake_timeouts_total 677
telemt_upstream_connect_attempt_total 17323
telemt_upstream_connect_success_total 17074
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 17323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 266
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 324
telemt_me_reconnect_attempts_total 40241
telemt_me_reconnect_success_total 9066
telemt_me_reader_eof_total 10212
telemt_me_idle_close_by_peer_total 10212
telemt_me_route_drop_no_conn_total 35225
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75891
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 10112
telemt_me_refill_failed_total 973
telemt_me_writer_restored_same_endpoint_total 9051
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1046
telemt_user_connections_total{user="hello"} 81926
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 884342367 (843.37 MB)
telemt_user_octets_to_client{user="hello"} 22716844383 (21.16 GB)
telemt_user_msgs_from_client{user="hello"} 95620
telemt_user_msgs_to_client{user="hello"} 658215
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 38714.4 (10h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112878
telemt_connections_bad_total 1513
telemt_handshake_timeouts_total 2108
telemt_upstream_connect_attempt_total 10795
telemt_upstream_connect_success_total 10795
telemt_upstream_connect_attempts_per_request{bucket="1"} 10795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5562
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 255
telemt_me_reconnect_attempts_total 8872
telemt_me_reconnect_success_total 8798
telemt_me_reader_eof_total 9296
telemt_me_idle_close_by_peer_total 9296
telemt_me_route_drop_no_conn_total 42311
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104651
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 8884
telemt_me_writer_restored_same_endpoint_total 8778
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 104624
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 2408632224 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 53778688920 (50.09 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 38690.4 (10h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153998
telemt_connections_bad_total 13099
telemt_handshake_timeouts_total 1167
telemt_upstream_connect_attempt_total 8836
telemt_upstream_connect_success_total 8566
telemt_upstream_connect_fail_total 270
telemt_upstream_connect_attempts_per_request{bucket="1"} 8836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4500
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 270
telemt_me_keepalive_timeout_total 377
telemt_me_reconnect_attempts_total 37230
telemt_me_reconnect_success_total 6610
telemt_me_reader_eof_total 7707
telemt_me_idle_close_by_peer_total 7707
telemt_me_route_drop_no_conn_total 56385
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132046
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 128
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 168
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 7636
telemt_me_refill_failed_total 955
telemt_me_writer_restored_same_endpoint_total 6602
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 1026
telemt_user_connections_total{user="hello"} 131928
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 2351553660 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 54077422604 (50.36 GB)
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 38659.7 (10h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 98617
telemt_connections_bad_total 9938
telemt_handshake_timeouts_total 1327
telemt_upstream_connect_attempt_total 52999
telemt_upstream_connect_success_total 52538
telemt_upstream_connect_fail_total 461
telemt_upstream_connect_attempts_per_request{bucket="1"} 52999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 461
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 53406
telemt_me_reconnect_success_total 3752
telemt_me_reader_eof_total 5301
telemt_me_idle_close_by_peer_total 5301
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 14069
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 36131
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 5329
telemt_me_refill_failed_total 1554
telemt_me_writer_restored_same_endpoint_total 3735
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1577
telemt_user_connections_total{user="hello"} 82966
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 739564770 (705.30 MB)
telemt_user_octets_to_client{user="hello"} 24395903468 (22.72 GB)
telemt_user_msgs_from_client{user="hello"} 718270
telemt_user_msgs_to_client{user="hello"} 2754718
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 38647.3 (10h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 246576
telemt_connections_bad_total 1357
telemt_handshake_timeouts_total 2092
telemt_upstream_connect_attempt_total 8206
telemt_upstream_connect_success_total 8167
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 8206
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_keepalive_timeout_total 466
telemt_me_reconnect_attempts_total 9819
telemt_me_reconnect_success_total 6216
telemt_me_reader_eof_total 6622
telemt_me_idle_close_by_peer_total 6621
telemt_me_route_drop_no_conn_total 113545
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245274
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 6409
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 6209
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 235201
telemt_user_connections_current{user="hello"} 392
telemt_user_octets_from_client{user="hello"} 4129282608 (3.85 GB)
telemt_user_octets_to_client{user="hello"} 108095417436 (100.67 GB)
telemt_user_unique_ips_current{user="hello"} 141
telemt_user_unique_ips_recent_window{user="hello"} 44
```