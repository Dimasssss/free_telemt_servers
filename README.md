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

# Server Metrics 2026-03-13 09:46:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 94395.8 (26h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 371519
telemt_connections_bad_total 3190
telemt_handshake_timeouts_total 7895
telemt_upstream_connect_attempt_total 23796
telemt_upstream_connect_success_total 23685
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 23796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1741
telemt_me_reconnect_attempts_total 22476
telemt_me_reconnect_success_total 18962
telemt_me_reader_eof_total 20262
telemt_me_idle_close_by_peer_total 20261
telemt_me_route_drop_no_conn_total 116427
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318907
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1021
telemt_desync_full_logged_total 380
telemt_desync_suppressed_total 641
telemt_desync_frames_bucket_total{bucket="1_2"} 212
telemt_desync_frames_bucket_total{bucket="3_10"} 370
telemt_desync_frames_bucket_total{bucket="gt_10"} 439
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 19272
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18946
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 318598
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 5429252896 (5.06 GB)
telemt_user_octets_to_client{user="hello"} 140758201380 (131.09 GB)
telemt_user_unique_ips_current{user="hello"} 115
telemt_user_unique_ips_recent_window{user="hello"} 51
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 94288.6 (26h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 170203
telemt_connections_bad_total 1546
telemt_handshake_timeouts_total 1302
telemt_upstream_connect_attempt_total 46857
telemt_upstream_connect_success_total 46217
telemt_upstream_connect_fail_total 640
telemt_upstream_connect_attempts_per_request{bucket="1"} 46857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19055
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 640
telemt_me_keepalive_timeout_total 730
telemt_me_reconnect_attempts_total 81388
telemt_me_reconnect_success_total 25019
telemt_me_reader_eof_total 27526
telemt_me_idle_close_by_peer_total 27526
telemt_me_route_drop_no_conn_total 71667
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143905
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
telemt_me_writer_removed_unexpected_total 26992
telemt_me_refill_failed_total 1759
telemt_me_writer_restored_same_endpoint_total 25004
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1973
telemt_user_connections_total{user="hello"} 160186
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 1676027740 (1.56 GB)
telemt_user_octets_to_client{user="hello"} 52600270415 (48.99 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 94252.1 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207169
telemt_connections_bad_total 2011
telemt_handshake_timeouts_total 4195
telemt_upstream_connect_attempt_total 25483
telemt_upstream_connect_success_total 25480
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11722
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13733
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 684
telemt_me_reconnect_attempts_total 21923
telemt_me_reconnect_success_total 20732
telemt_me_reader_eof_total 22224
telemt_me_idle_close_by_peer_total 22224
telemt_me_route_drop_no_conn_total 78270
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 193329
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
telemt_me_writer_removed_unexpected_total 20960
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20712
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 228
telemt_user_connections_total{user="hello"} 193251
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 8421712892 (7.84 GB)
telemt_user_octets_to_client{user="hello"} 80968543928 (75.41 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 94227.8 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294141
telemt_connections_bad_total 13665
telemt_handshake_timeouts_total 2147
telemt_upstream_connect_attempt_total 38488
telemt_upstream_connect_success_total 28475
telemt_upstream_connect_fail_total 10013
telemt_upstream_connect_attempts_per_request{bucket="1"} 38488
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14255
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14023
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10013
telemt_me_keepalive_timeout_total 3425
telemt_me_reconnect_attempts_total 78828
telemt_me_reconnect_success_total 20912
telemt_me_reader_eof_total 23364
telemt_me_idle_close_by_peer_total 23357
telemt_me_route_drop_no_conn_total 106466
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251723
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 934
telemt_desync_full_logged_total 275
telemt_desync_suppressed_total 659
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 351
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22986
telemt_me_refill_failed_total 1805
telemt_me_writer_restored_same_endpoint_total 20902
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2074
telemt_user_connections_total{user="hello"} 254446
telemt_user_connections_current{user="hello"} 163
telemt_user_octets_from_client{user="hello"} 5581437314 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 95702233201 (89.13 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 44399.4 (12h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58536
telemt_connections_bad_total 8922
telemt_handshake_timeouts_total 490
telemt_upstream_connect_attempt_total 15311
telemt_upstream_connect_success_total 15162
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 15310
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6652
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 375
telemt_me_reconnect_attempts_total 15152
telemt_me_reconnect_success_total 12923
telemt_me_reader_eof_total 13782
telemt_me_idle_close_by_peer_total 13782
telemt_me_route_drop_no_conn_total 17973
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47396
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
telemt_me_writer_removed_unexpected_total 13109
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12905
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 47391
telemt_user_connections_current{user="hello"} 98
telemt_user_octets_from_client{user="hello"} 359865636 (343.19 MB)
telemt_user_octets_to_client{user="hello"} 12905304132 (12.02 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 94184.5 (26h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 510961
telemt_connections_bad_total 14342
telemt_handshake_timeouts_total 5987
telemt_upstream_connect_attempt_total 20062
telemt_upstream_connect_success_total 19956
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 20062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 1551
telemt_me_reconnect_attempts_total 18926
telemt_me_reconnect_success_total 15275
telemt_me_reader_eof_total 16392
telemt_me_idle_close_by_peer_total 16389
telemt_me_route_drop_no_conn_total 265337
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 499499
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 400
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 145
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 15585
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 15268
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 472588
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 8554070464 (7.97 GB)
telemt_user_octets_to_client{user="hello"} 266207493584 (247.93 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 69
```