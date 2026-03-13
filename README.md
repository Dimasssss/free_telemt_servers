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

# Server Metrics 2026-03-13 10:22:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 96571.0 (26h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 383895
telemt_connections_bad_total 3192
telemt_handshake_timeouts_total 8087
telemt_upstream_connect_attempt_total 24413
telemt_upstream_connect_success_total 24301
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 24413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10935
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1765
telemt_me_reconnect_attempts_total 22959
telemt_me_reconnect_success_total 19440
telemt_me_reader_eof_total 20771
telemt_me_idle_close_by_peer_total 20770
telemt_me_route_drop_no_conn_total 119948
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 330538
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1073
telemt_desync_full_logged_total 396
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 19751
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19424
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 311
telemt_user_connections_total{user="hello"} 330242
telemt_user_connections_current{user="hello"} 382
telemt_user_octets_from_client{user="hello"} 5847968808 (5.45 GB)
telemt_user_octets_to_client{user="hello"} 143175546048 (133.34 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 96463.9 (26h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175796
telemt_connections_bad_total 1563
telemt_handshake_timeouts_total 1329
telemt_upstream_connect_attempt_total 47430
telemt_upstream_connect_success_total 46775
telemt_upstream_connect_fail_total 655
telemt_upstream_connect_attempts_per_request{bucket="1"} 47430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26907
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 655
telemt_me_keepalive_timeout_total 747
telemt_me_reconnect_attempts_total 85004
telemt_me_reconnect_success_total 25441
telemt_me_reader_eof_total 28051
telemt_me_idle_close_by_peer_total 28051
telemt_me_route_drop_no_conn_total 75213
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 149236
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 27517
telemt_me_refill_failed_total 1858
telemt_me_writer_restored_same_endpoint_total 25425
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2076
telemt_user_connections_total{user="hello"} 165516
telemt_user_connections_current{user="hello"} 171
telemt_user_octets_from_client{user="hello"} 1720482520 (1.60 GB)
telemt_user_octets_to_client{user="hello"} 55178103803 (51.39 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 96428.1 (26h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 214136
telemt_connections_bad_total 2047
telemt_handshake_timeouts_total 4323
telemt_upstream_connect_attempt_total 26121
telemt_upstream_connect_success_total 26118
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 26121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14056
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 742
telemt_me_reconnect_attempts_total 22427
telemt_me_reconnect_success_total 21230
telemt_me_reader_eof_total 22758
telemt_me_idle_close_by_peer_total 22758
telemt_me_route_drop_no_conn_total 80365
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 199943
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 21462
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21210
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 199864
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 9184388444 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 81977265636 (76.35 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 96403.4 (26h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 302590
telemt_connections_bad_total 13675
telemt_handshake_timeouts_total 2230
telemt_upstream_connect_attempt_total 38889
telemt_upstream_connect_success_total 28861
telemt_upstream_connect_fail_total 10028
telemt_upstream_connect_attempts_per_request{bucket="1"} 38889
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14194
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10028
telemt_me_keepalive_timeout_total 3434
telemt_me_reconnect_attempts_total 81747
telemt_me_reconnect_success_total 21175
telemt_me_reader_eof_total 23713
telemt_me_idle_close_by_peer_total 23706
telemt_me_route_drop_no_conn_total 109164
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 259621
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 966
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23335
telemt_me_refill_failed_total 1888
telemt_me_writer_restored_same_endpoint_total 21165
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2160
telemt_user_connections_total{user="hello"} 262343
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 5661890942 (5.27 GB)
telemt_user_octets_to_client{user="hello"} 98229300993 (91.48 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 46574.7 (12h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62761
telemt_connections_bad_total 9311
telemt_handshake_timeouts_total 492
telemt_upstream_connect_attempt_total 16198
telemt_upstream_connect_success_total 16042
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 16198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8948
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 400
telemt_me_reconnect_attempts_total 15944
telemt_me_reconnect_success_total 13713
telemt_me_reader_eof_total 14580
telemt_me_idle_close_by_peer_total 14580
telemt_me_route_drop_no_conn_total 19549
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51098
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 13907
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 13695
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 51093
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 467124424 (445.48 MB)
telemt_user_octets_to_client{user="hello"} 13640679868 (12.70 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 96359.7 (26h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 528862
telemt_connections_bad_total 14507
telemt_handshake_timeouts_total 8073
telemt_upstream_connect_attempt_total 20581
telemt_upstream_connect_success_total 20474
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 20581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10856
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1582
telemt_me_reconnect_attempts_total 19329
telemt_me_reconnect_success_total 15673
telemt_me_reader_eof_total 16802
telemt_me_idle_close_by_peer_total 16799
telemt_me_route_drop_no_conn_total 271053
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 514625
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 427
telemt_desync_full_logged_total 163
telemt_desync_suppressed_total 264
telemt_desync_frames_bucket_total{bucket="1_2"} 105
telemt_desync_frames_bucket_total{bucket="3_10"} 157
telemt_desync_frames_bucket_total{bucket="gt_10"} 165
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 15995
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15666
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 322
telemt_user_connections_total{user="hello"} 487707
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 8731657432 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 273842638144 (255.04 GB)
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 73
```