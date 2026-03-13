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

# Server Metrics 2026-03-13 07:23:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 85791.8 (23h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 328654
telemt_connections_bad_total 3167
telemt_handshake_timeouts_total 7176
telemt_upstream_connect_attempt_total 21568
telemt_upstream_connect_success_total 21469
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 21568
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9672
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11749
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1651
telemt_me_reconnect_attempts_total 20657
telemt_me_reconnect_success_total 17153
telemt_me_reader_eof_total 18348
telemt_me_idle_close_by_peer_total 18347
telemt_me_route_drop_no_conn_total 103134
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 279141
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 944
telemt_desync_full_logged_total 349
telemt_desync_suppressed_total 595
telemt_desync_frames_bucket_total{bucket="1_2"} 187
telemt_desync_frames_bucket_total{bucket="3_10"} 345
telemt_desync_frames_bucket_total{bucket="gt_10"} 412
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 17446
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 17137
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 293
telemt_user_connections_total{user="hello"} 278836
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 4671324616 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 131054268132 (122.05 GB)
telemt_user_unique_ips_current{user="hello"} 99
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 85684.8 (23h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 149725
telemt_connections_bad_total 1425
telemt_handshake_timeouts_total 1150
telemt_upstream_connect_attempt_total 44370
telemt_upstream_connect_success_total 43776
telemt_upstream_connect_fail_total 594
telemt_upstream_connect_attempts_per_request{bucket="1"} 44370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17614
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 511
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 594
telemt_me_keepalive_timeout_total 663
telemt_me_reconnect_attempts_total 73807
telemt_me_reconnect_success_total 22980
telemt_me_reader_eof_total 25251
telemt_me_idle_close_by_peer_total 25251
telemt_me_route_drop_no_conn_total 56522
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125241
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 18
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
telemt_me_writer_removed_unexpected_total 24750
telemt_me_refill_failed_total 1586
telemt_me_writer_restored_same_endpoint_total 22965
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1770
telemt_user_connections_total{user="hello"} 141733
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 1458830592 (1.36 GB)
telemt_user_octets_to_client{user="hello"} 45729963443 (42.59 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 85648.3 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181802
telemt_connections_bad_total 1971
telemt_handshake_timeouts_total 2938
telemt_upstream_connect_attempt_total 23324
telemt_upstream_connect_success_total 23322
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 23324
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12559
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 559
telemt_me_reconnect_attempts_total 20161
telemt_me_reconnect_success_total 18986
telemt_me_reader_eof_total 20358
telemt_me_idle_close_by_peer_total 20358
telemt_me_route_drop_no_conn_total 70180
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 170134
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
telemt_pool_swap_total 79
telemt_me_writer_removed_unexpected_total 19192
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18966
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 170063
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 3015642404 (2.81 GB)
telemt_user_octets_to_client{user="hello"} 74075505576 (68.99 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 85624.0 (23h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 261108
telemt_connections_bad_total 13616
telemt_handshake_timeouts_total 1997
telemt_upstream_connect_attempt_total 35980
telemt_upstream_connect_success_total 26034
telemt_upstream_connect_fail_total 9946
telemt_upstream_connect_attempts_per_request{bucket="1"} 35980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13047
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12801
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 177
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9946
telemt_me_keepalive_timeout_total 3360
telemt_me_reconnect_attempts_total 70419
telemt_me_reconnect_success_total 18879
telemt_me_reader_eof_total 21093
telemt_me_idle_close_by_peer_total 21086
telemt_me_route_drop_no_conn_total 94283
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220774
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 739
telemt_desync_full_logged_total 211
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 179
telemt_desync_frames_bucket_total{bucket="3_10"} 280
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 20735
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18869
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1856
telemt_user_connections_total{user="hello"} 223506
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 5198515722 (4.84 GB)
telemt_user_octets_to_client{user="hello"} 85810058541 (79.92 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 35795.6 (9h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43367
telemt_connections_bad_total 7369
telemt_handshake_timeouts_total 392
telemt_upstream_connect_attempt_total 12126
telemt_upstream_connect_success_total 12003
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 12126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5213
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6748
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 291
telemt_me_reconnect_attempts_total 11183
telemt_me_reconnect_success_total 10215
telemt_me_reader_eof_total 10902
telemt_me_idle_close_by_peer_total 10902
telemt_me_route_drop_no_conn_total 12382
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34510
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 35
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 10338
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 10197
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 34509
telemt_user_connections_current{user="hello"} 80
telemt_user_octets_from_client{user="hello"} 251133832 (239.50 MB)
telemt_user_octets_to_client{user="hello"} 10859252088 (10.11 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 85580.4 (23h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443052
telemt_connections_bad_total 8915
telemt_handshake_timeouts_total 3347
telemt_upstream_connect_attempt_total 18199
telemt_upstream_connect_success_total 18101
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 18199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8456
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9620
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_timeout_total 1502
telemt_me_reconnect_attempts_total 17477
telemt_me_reconnect_success_total 13839
telemt_me_reader_eof_total 14860
telemt_me_idle_close_by_peer_total 14857
telemt_me_route_drop_no_conn_total 197994
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 428292
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 363
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 130
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 14127
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13832
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 415551
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 7780090536 (7.25 GB)
telemt_user_octets_to_client{user="hello"} 241524280556 (224.94 GB)
telemt_user_unique_ips_current{user="hello"} 145
telemt_user_unique_ips_recent_window{user="hello"} 46
```