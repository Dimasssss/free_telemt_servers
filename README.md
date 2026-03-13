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

# Server Metrics 2026-03-13 09:36:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 93781.0 (26h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 368394
telemt_connections_bad_total 3189
telemt_handshake_timeouts_total 7848
telemt_upstream_connect_attempt_total 23686
telemt_upstream_connect_success_total 23575
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 23686
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10628
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1715
telemt_me_reconnect_attempts_total 22366
telemt_me_reconnect_success_total 18853
telemt_me_reader_eof_total 20151
telemt_me_idle_close_by_peer_total 20150
telemt_me_route_drop_no_conn_total 115749
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 315988
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1014
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 638
telemt_desync_frames_bucket_total{bucket="1_2"} 211
telemt_desync_frames_bucket_total{bucket="3_10"} 368
telemt_desync_frames_bucket_total{bucket="gt_10"} 435
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 19161
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18837
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 308
telemt_user_connections_total{user="hello"} 315677
telemt_user_connections_current{user="hello"} 350
telemt_user_octets_from_client{user="hello"} 5217555648 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 140313455204 (130.68 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 93673.8 (26h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 168566
telemt_connections_bad_total 1543
telemt_handshake_timeouts_total 1298
telemt_upstream_connect_attempt_total 46643
telemt_upstream_connect_success_total 46006
telemt_upstream_connect_fail_total 636
telemt_upstream_connect_attempts_per_request{bucket="1"} 46642
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18933
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 516
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 636
telemt_me_keepalive_timeout_total 717
telemt_me_reconnect_attempts_total 80212
telemt_me_reconnect_success_total 24835
telemt_me_reader_eof_total 27307
telemt_me_idle_close_by_peer_total 27307
telemt_me_route_drop_no_conn_total 64634
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142140
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 26773
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 24820
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1938
telemt_user_connections_total{user="hello"} 158632
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 1661119348 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 51654622751 (48.11 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 93637.2 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205308
telemt_connections_bad_total 2007
telemt_handshake_timeouts_total 4167
telemt_upstream_connect_attempt_total 25264
telemt_upstream_connect_success_total 25261
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25264
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11605
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 641
telemt_me_reconnect_attempts_total 21740
telemt_me_reconnect_success_total 20551
telemt_me_reader_eof_total 22042
telemt_me_idle_close_by_peer_total 22042
telemt_me_route_drop_no_conn_total 77507
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 191583
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
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 20778
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20531
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 191507
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 7852666884 (7.31 GB)
telemt_user_octets_to_client{user="hello"} 79610172720 (74.14 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 93612.9 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 292012
telemt_connections_bad_total 13664
telemt_handshake_timeouts_total 2143
telemt_upstream_connect_attempt_total 38340
telemt_upstream_connect_success_total 28334
telemt_upstream_connect_fail_total 10006
telemt_upstream_connect_attempts_per_request{bucket="1"} 38340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14174
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13963
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10006
telemt_me_keepalive_timeout_total 3425
telemt_me_reconnect_attempts_total 77453
telemt_me_reconnect_success_total 20817
telemt_me_reader_eof_total 23226
telemt_me_idle_close_by_peer_total 23219
telemt_me_route_drop_no_conn_total 105514
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 249695
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 923
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 653
telemt_desync_frames_bucket_total{bucket="1_2"} 231
telemt_desync_frames_bucket_total{bucket="3_10"} 343
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22848
telemt_me_refill_failed_total 1765
telemt_me_writer_restored_same_endpoint_total 20807
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2031
telemt_user_connections_total{user="hello"} 252418
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 5565500830 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 95242917465 (88.70 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 43784.5 (12h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57501
telemt_connections_bad_total 8810
telemt_handshake_timeouts_total 486
telemt_upstream_connect_attempt_total 15123
telemt_upstream_connect_success_total 14977
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 15123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 360
telemt_me_reconnect_attempts_total 15009
telemt_me_reconnect_success_total 12783
telemt_me_reader_eof_total 13623
telemt_me_idle_close_by_peer_total 13623
telemt_me_route_drop_no_conn_total 17531
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46559
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
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 12966
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12765
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 46554
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 350083780 (333.87 MB)
telemt_user_octets_to_client{user="hello"} 12696540748 (11.82 GB)
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 93569.5 (25h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 505122
telemt_connections_bad_total 13915
telemt_handshake_timeouts_total 5481
telemt_upstream_connect_attempt_total 19922
telemt_upstream_connect_success_total 19816
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 19922
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10508
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1544
telemt_me_reconnect_attempts_total 18829
telemt_me_reconnect_success_total 15182
telemt_me_reader_eof_total 16278
telemt_me_idle_close_by_peer_total 16275
telemt_me_route_drop_no_conn_total 263300
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 494803
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 398
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 15491
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15175
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 467892
telemt_user_connections_current{user="hello"} 517
telemt_user_octets_from_client{user="hello"} 8509227420 (7.92 GB)
telemt_user_octets_to_client{user="hello"} 263916786744 (245.79 GB)
telemt_user_unique_ips_current{user="hello"} 177
telemt_user_unique_ips_recent_window{user="hello"} 66
```