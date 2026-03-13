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

# Server Metrics 2026-03-13 06:52:32 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 83948.0 (23h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318270
telemt_connections_bad_total 3139
telemt_handshake_timeouts_total 6724
telemt_upstream_connect_attempt_total 21155
telemt_upstream_connect_success_total 21057
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 21155
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9486
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11523
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1622
telemt_me_reconnect_attempts_total 20333
telemt_me_reconnect_success_total 16830
telemt_me_reader_eof_total 18000
telemt_me_idle_close_by_peer_total 17999
telemt_me_route_drop_no_conn_total 99084
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269506
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 928
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 17120
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16814
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 269437
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 4557054136 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 127435822984 (118.68 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 55
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 83840.6 (23h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145857
telemt_connections_bad_total 1422
telemt_handshake_timeouts_total 1092
telemt_upstream_connect_attempt_total 43586
telemt_upstream_connect_success_total 43014
telemt_upstream_connect_fail_total 572
telemt_upstream_connect_attempts_per_request{bucket="1"} 43586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25361
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17144
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 572
telemt_me_keepalive_timeout_total 635
telemt_me_reconnect_attempts_total 71499
telemt_me_reconnect_success_total 22306
telemt_me_reader_eof_total 24519
telemt_me_idle_close_by_peer_total 24519
telemt_me_route_drop_no_conn_total 55071
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121544
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
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
telemt_me_writer_removed_unexpected_total 24018
telemt_me_refill_failed_total 1535
telemt_me_writer_restored_same_endpoint_total 22291
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1712
telemt_user_connections_total{user="hello"} 138039
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 1431373908 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 45023305431 (41.93 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 83804.3 (23h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176889
telemt_connections_bad_total 1912
telemt_handshake_timeouts_total 2889
telemt_upstream_connect_attempt_total 22899
telemt_upstream_connect_success_total 22897
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 19823
telemt_me_reconnect_success_total 18650
telemt_me_reader_eof_total 19990
telemt_me_idle_close_by_peer_total 19990
telemt_me_route_drop_no_conn_total 68091
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165516
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
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 18850
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18630
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 165443
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 2980043056 (2.78 GB)
telemt_user_octets_to_client{user="hello"} 73473943960 (68.43 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 83780.0 (23h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 254555
telemt_connections_bad_total 13611
telemt_handshake_timeouts_total 1948
telemt_upstream_connect_attempt_total 35424
telemt_upstream_connect_success_total 25489
telemt_upstream_connect_fail_total 9933
telemt_upstream_connect_attempts_per_request{bucket="1"} 35422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12521
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 176
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9933
telemt_me_keepalive_timeout_total 3352
telemt_me_reconnect_attempts_total 69980
telemt_me_reconnect_success_total 18442
telemt_me_reader_eof_total 20623
telemt_me_idle_close_by_peer_total 20616
telemt_me_route_drop_no_conn_total 92058
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 214656
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 647
telemt_desync_full_logged_total 189
telemt_desync_suppressed_total 458
telemt_desync_frames_bucket_total{bucket="1_2"} 162
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 240
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 20289
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18432
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1847
telemt_user_connections_total{user="hello"} 217388
telemt_user_connections_current{user="hello"} 161
telemt_user_octets_from_client{user="hello"} 4325362878 (4.03 GB)
telemt_user_octets_to_client{user="hello"} 83908202065 (78.15 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 57
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 33951.4 (9h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39729
telemt_connections_bad_total 7038
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 11631
telemt_upstream_connect_success_total 11515
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 11631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5004
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6470
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 277
telemt_me_reconnect_attempts_total 10781
telemt_me_reconnect_success_total 9814
telemt_me_reader_eof_total 10466
telemt_me_idle_close_by_peer_total 10466
telemt_me_route_drop_no_conn_total 11251
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31499
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 9930
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9796
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 31499
telemt_user_connections_current{user="hello"} 47
telemt_user_octets_from_client{user="hello"} 237422612 (226.42 MB)
telemt_user_octets_to_client{user="hello"} 10372327652 (9.66 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 83736.2 (23h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 430793
telemt_connections_bad_total 8859
telemt_handshake_timeouts_total 3269
telemt_upstream_connect_attempt_total 17820
telemt_upstream_connect_success_total 17723
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17820
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9441
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 1457
telemt_me_reconnect_attempts_total 17207
telemt_me_reconnect_success_total 13573
telemt_me_reader_eof_total 14574
telemt_me_idle_close_by_peer_total 14571
telemt_me_route_drop_no_conn_total 190467
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416239
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 361
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 13857
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13566
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 404472
telemt_user_connections_current{user="hello"} 436
telemt_user_octets_from_client{user="hello"} 6557227812 (6.11 GB)
telemt_user_octets_to_client{user="hello"} 234782408900 (218.66 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 66
```