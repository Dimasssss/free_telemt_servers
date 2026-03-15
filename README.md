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

# Server Metrics 2026-03-15 12:25:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 51048.3 (14h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 222636
telemt_connections_bad_total 1703
telemt_handshake_timeouts_total 4661
telemt_upstream_connect_attempt_total 12960
telemt_upstream_connect_success_total 12890
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 12960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7156
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13708
telemt_me_reconnect_success_total 10336
telemt_me_reader_eof_total 11041
telemt_me_idle_close_by_peer_total 11041
telemt_me_route_drop_no_conn_total 425463
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268822
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1541
telemt_desync_full_logged_total 611
telemt_desync_suppressed_total 930
telemt_desync_frames_bucket_total{bucket="1_2"} 253
telemt_desync_frames_bucket_total{bucket="3_10"} 616
telemt_desync_frames_bucket_total{bucket="gt_10"} 672
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10546
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10305
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 210
telemt_user_connections_total{user="hello"} 207933
telemt_user_connections_current{user="hello"} 375
telemt_user_octets_from_client{user="hello"} 4054920648 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 193858325792 (180.54 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 51054.7 (14h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78734
telemt_connections_bad_total 2659
telemt_handshake_timeouts_total 5797
telemt_upstream_connect_attempt_total 13906
telemt_upstream_connect_success_total 13906
telemt_upstream_connect_attempts_per_request{bucket="1"} 13906
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13664
telemt_me_reconnect_success_total 11328
telemt_me_reader_eof_total 12134
telemt_me_idle_close_by_peer_total 12134
telemt_me_route_drop_no_conn_total 35366
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 67767
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11523
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11312
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 195
telemt_user_connections_total{user="hello"} 67765
telemt_user_connections_current{user="hello"} 238
telemt_user_octets_from_client{user="hello"} 1380506256 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 30800740976 (28.69 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 51047.4 (14h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 82467
telemt_connections_bad_total 1033
telemt_handshake_timeouts_total 2587
telemt_upstream_connect_attempt_total 14836
telemt_upstream_connect_success_total 14828
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 14836
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6450
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8351
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 14392
telemt_me_reconnect_success_total 12248
telemt_me_reader_eof_total 13088
telemt_me_idle_close_by_peer_total 13088
telemt_me_route_drop_no_conn_total 31736
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75227
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 12431
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12240
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 75141
telemt_user_connections_current{user="hello"} 170
telemt_user_octets_from_client{user="hello"} 9554383400 (8.90 GB)
telemt_user_octets_to_client{user="hello"} 44894418888 (41.81 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 51047.0 (14h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112175
telemt_connections_bad_total 393
telemt_handshake_timeouts_total 718
telemt_upstream_connect_attempt_total 12000
telemt_upstream_connect_success_total 11998
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5738
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9503
telemt_me_reconnect_success_total 9449
telemt_me_reader_eof_total 10078
telemt_me_idle_close_by_peer_total 10078
telemt_me_route_drop_no_conn_total 44798
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 102414
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 277
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 69
telemt_desync_frames_bucket_total{bucket="3_10"} 115
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9557
telemt_me_writer_restored_same_endpoint_total 9438
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 102334
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 1793776816 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 56186329088 (52.33 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 26118.6 (7h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 59925
telemt_connections_bad_total 15378
telemt_handshake_timeouts_total 868
telemt_upstream_connect_attempt_total 8422
telemt_upstream_connect_success_total 8363
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 8422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4574
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 101309
telemt_me_reconnect_success_total 6891
telemt_me_reader_eof_total 7176
telemt_me_idle_close_by_peer_total 7176
telemt_me_route_drop_no_conn_total 20976
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 42321
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 102
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 6881
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6787
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 42457
telemt_user_connections_current{user="hello"} 83
telemt_user_octets_from_client{user="hello"} 658554533 (628.05 MB)
telemt_user_octets_to_client{user="hello"} 16902792727 (15.74 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 51046.2 (14h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292941
telemt_connections_bad_total 47709
telemt_handshake_timeouts_total 2142
telemt_upstream_connect_attempt_total 10821
telemt_upstream_connect_success_total 10755
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5372
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_reconnect_attempts_total 8249
telemt_me_reconnect_success_total 8194
telemt_me_reader_eof_total 8718
telemt_me_idle_close_by_peer_total 8718
telemt_me_route_drop_no_conn_total 130424
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234504
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 144
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 61
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8264
telemt_me_writer_restored_same_endpoint_total 8167
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 232864
telemt_user_connections_current{user="hello"} 595
telemt_user_octets_from_client{user="hello"} 4972841732 (4.63 GB)
telemt_user_octets_to_client{user="hello"} 113335610656 (105.55 GB)
telemt_user_unique_ips_current{user="hello"} 223
telemt_user_unique_ips_recent_window{user="hello"} 85
```