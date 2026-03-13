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

# Server Metrics 2026-03-13 08:14:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 88863.7 (24h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 344185
telemt_connections_bad_total 3172
telemt_handshake_timeouts_total 7547
telemt_upstream_connect_attempt_total 22243
telemt_upstream_connect_success_total 22141
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 22243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9956
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1659
telemt_me_reconnect_attempts_total 21196
telemt_me_reconnect_success_total 17690
telemt_me_reader_eof_total 18923
telemt_me_idle_close_by_peer_total 18922
telemt_me_route_drop_no_conn_total 107544
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 293693
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 970
telemt_desync_full_logged_total 360
telemt_desync_suppressed_total 610
telemt_desync_frames_bucket_total{bucket="1_2"} 195
telemt_desync_frames_bucket_total{bucket="3_10"} 355
telemt_desync_frames_bucket_total{bucket="gt_10"} 420
telemt_pool_swap_total 81
telemt_me_writer_removed_unexpected_total 17988
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17674
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 298
telemt_user_connections_total{user="hello"} 293384
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 4839781768 (4.51 GB)
telemt_user_octets_to_client{user="hello"} 135007221220 (125.74 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 88756.6 (24h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156754
telemt_connections_bad_total 1492
telemt_handshake_timeouts_total 1204
telemt_upstream_connect_attempt_total 45104
telemt_upstream_connect_success_total 44493
telemt_upstream_connect_fail_total 611
telemt_upstream_connect_attempts_per_request{bucket="1"} 45104
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18028
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 512
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 611
telemt_me_keepalive_timeout_total 679
telemt_me_reconnect_attempts_total 78936
telemt_me_reconnect_success_total 23565
telemt_me_reader_eof_total 25987
telemt_me_idle_close_by_peer_total 25987
telemt_me_route_drop_no_conn_total 59141
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 131672
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 25486
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 23550
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1921
telemt_user_connections_total{user="hello"} 148164
telemt_user_connections_current{user="hello"} 151
telemt_user_octets_from_client{user="hello"} 1537031424 (1.43 GB)
telemt_user_octets_to_client{user="hello"} 47633392827 (44.36 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 88720.5 (24h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 189131
telemt_connections_bad_total 1984
telemt_handshake_timeouts_total 3125
telemt_upstream_connect_attempt_total 24057
telemt_upstream_connect_success_total 24055
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 24057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12973
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 573
telemt_me_reconnect_attempts_total 20765
telemt_me_reconnect_success_total 19586
telemt_me_reader_eof_total 21009
telemt_me_idle_close_by_peer_total 21009
telemt_me_route_drop_no_conn_total 72855
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 177026
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 82
telemt_me_writer_removed_unexpected_total 19800
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 19566
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 176956
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 6639108280 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 75147269880 (69.99 GB)
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 88695.9 (24h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274435
telemt_connections_bad_total 13647
telemt_handshake_timeouts_total 2037
telemt_upstream_connect_attempt_total 36838
telemt_upstream_connect_success_total 26877
telemt_upstream_connect_fail_total 9961
telemt_upstream_connect_attempts_per_request{bucket="1"} 36838
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13257
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 180
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9961
telemt_me_keepalive_timeout_total 3381
telemt_me_reconnect_attempts_total 71130
telemt_me_reconnect_success_total 19585
telemt_me_reader_eof_total 21827
telemt_me_idle_close_by_peer_total 21820
telemt_me_route_drop_no_conn_total 99060
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 233004
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 858
telemt_desync_full_logged_total 252
telemt_desync_suppressed_total 606
telemt_desync_frames_bucket_total{bucket="1_2"} 215
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 323
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 21449
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 19575
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1864
telemt_user_connections_total{user="hello"} 235730
telemt_user_connections_current{user="hello"} 202
telemt_user_octets_from_client{user="hello"} 5258152578 (4.90 GB)
telemt_user_octets_to_client{user="hello"} 89290931745 (83.16 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 38867.4 (10h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 48607
telemt_connections_bad_total 7924
telemt_handshake_timeouts_total 410
telemt_upstream_connect_attempt_total 13313
telemt_upstream_connect_success_total 13176
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 13313
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5741
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 316
telemt_me_reconnect_attempts_total 12178
telemt_me_reconnect_success_total 11207
telemt_me_reader_eof_total 11925
telemt_me_idle_close_by_peer_total 11925
telemt_me_route_drop_no_conn_total 14465
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38923
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 71
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 62
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11335
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 11189
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 38922
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 279057340 (266.13 MB)
telemt_user_octets_to_client{user="hello"} 11274474508 (10.50 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 88652.5 (24h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 469291
telemt_connections_bad_total 13315
telemt_handshake_timeouts_total 4027
telemt_upstream_connect_attempt_total 18773
telemt_upstream_connect_success_total 18672
telemt_upstream_connect_fail_total 101
telemt_upstream_connect_attempts_per_request{bucket="1"} 18773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8731
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9916
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 101
telemt_me_keepalive_timeout_total 1527
telemt_me_reconnect_attempts_total 17907
telemt_me_reconnect_success_total 14266
telemt_me_reader_eof_total 15323
telemt_me_idle_close_by_peer_total 15320
telemt_me_route_drop_no_conn_total 235150
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 457840
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 373
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 229
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 149
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 14560
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14259
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 294
telemt_user_connections_total{user="hello"} 435210
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 8047709404 (7.50 GB)
telemt_user_octets_to_client{user="hello"} 250468251148 (233.27 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 65
```