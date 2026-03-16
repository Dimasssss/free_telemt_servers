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

# Server Metrics 2026-03-16 16:50:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 11571.7 (3h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122422
telemt_connections_bad_total 615
telemt_handshake_timeouts_total 3734
telemt_upstream_connect_attempt_total 2497
telemt_upstream_connect_success_total 2488
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 2497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1202
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1284
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 3032
telemt_me_reconnect_success_total 1862
telemt_me_reader_eof_total 1928
telemt_me_idle_close_by_peer_total 1928
telemt_me_route_drop_no_conn_total 36912
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114059
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 595
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 460
telemt_desync_frames_bucket_total{bucket="1_2"} 241
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 1908
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 1860
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 36
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 113979
telemt_user_connections_current{user="hello"} 706
telemt_user_octets_from_client{user="hello"} 2083029236 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 65806400616 (61.29 GB)
telemt_user_unique_ips_current{user="hello"} 211
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 6350.3 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44594
telemt_connections_bad_total 410
telemt_handshake_timeouts_total 1399
telemt_upstream_connect_attempt_total 1410
telemt_upstream_connect_success_total 1400
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 3239
telemt_me_reconnect_success_total 1046
telemt_me_reader_eof_total 1115
telemt_me_idle_close_by_peer_total 1115
telemt_me_route_drop_no_conn_total 28547
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 41365
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 65
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 1134
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 1041
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 343
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 41325
telemt_user_connections_current{user="hello"} 458
telemt_user_octets_from_client{user="hello"} 519604664 (495.53 MB)
telemt_user_octets_to_client{user="hello"} 13056778884 (12.16 GB)
telemt_user_unique_ips_current{user="hello"} 121
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 11684.6 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48000
telemt_connections_bad_total 60
telemt_handshake_timeouts_total 740
telemt_upstream_connect_attempt_total 3383
telemt_upstream_connect_success_total 3342
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 3383
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1859
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_reconnect_attempts_total 39498
telemt_me_reconnect_success_total 1738
telemt_me_reader_eof_total 2003
telemt_me_idle_close_by_peer_total 2003
telemt_me_route_drop_no_conn_total 16614
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43654
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 9
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 40
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2028
telemt_me_refill_failed_total 1179
telemt_me_writer_restored_same_endpoint_total 1694
telemt_me_writer_restored_fallback_total 44
telemt_me_async_recovery_trigger_total 1272
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 44597
telemt_user_connections_current{user="hello"} 275
telemt_user_octets_from_client{user="hello"} 546956286 (521.62 MB)
telemt_user_octets_to_client{user="hello"} 10413883290 (9.70 GB)
telemt_user_msgs_from_client{user="hello"} 4789
telemt_user_msgs_to_client{user="hello"} 14129
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 11821.0 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 92823
telemt_connections_bad_total 160
telemt_handshake_timeouts_total 1646
telemt_upstream_connect_attempt_total 2487
telemt_upstream_connect_success_total 2467
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 2487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1276
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 8121
telemt_me_reconnect_success_total 1772
telemt_me_reader_eof_total 1991
telemt_me_idle_close_by_peer_total 1991
telemt_me_route_drop_no_conn_total 35916
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87742
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 1
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 503
telemt_desync_full_logged_total 131
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 217
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1991
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 1768
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 87720
telemt_user_connections_current{user="hello"} 454
telemt_user_octets_from_client{user="hello"} 1270727152 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 22919015120 (21.34 GB)
telemt_user_unique_ips_current{user="hello"} 132
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 9281.4 (2h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54713
telemt_connections_bad_total 18784
telemt_handshake_timeouts_total 418
telemt_upstream_connect_attempt_total 2333
telemt_upstream_connect_success_total 2302
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 2333
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1334
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 2439
telemt_me_reconnect_success_total 1779
telemt_me_reader_eof_total 1840
telemt_me_idle_close_by_peer_total 1840
telemt_me_route_drop_no_conn_total 45770
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52645
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 43
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 27
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 1828
telemt_me_refill_failed_total 20
telemt_me_writer_restored_same_endpoint_total 1779
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 33699
telemt_user_connections_current{user="hello"} 236
telemt_user_octets_from_client{user="hello"} 1926218148 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 26563207996 (24.74 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 11389.3 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132928
telemt_connections_bad_total 1374
telemt_handshake_timeouts_total 3007
telemt_upstream_connect_attempt_total 2502
telemt_upstream_connect_success_total 2502
telemt_upstream_connect_attempts_per_request{bucket="1"} 2502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1215
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 6900
telemt_me_reconnect_success_total 1877
telemt_me_reader_eof_total 2046
telemt_me_idle_close_by_peer_total 2046
telemt_me_route_drop_no_conn_total 61090
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 123648
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 5
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 36
telemt_desync_full_logged_total 14
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2046
telemt_me_refill_failed_total 156
telemt_me_writer_restored_same_endpoint_total 1872
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 208
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 123365
telemt_user_connections_current{user="hello"} 780
telemt_user_octets_from_client{user="hello"} 2436840868 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 45779798604 (42.64 GB)
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 111
```