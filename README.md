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

## 4vps.su
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

# Server Metrics 2026-03-19 10:29:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 45648.4 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1019174
telemt_connections_bad_total 89574
telemt_connections_current 1470
telemt_connections_me_current 1470
telemt_handshake_timeouts_total 36874
telemt_upstream_connect_attempt_total 8651
telemt_upstream_connect_success_total 8499
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 8651
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4395
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 90
telemt_me_reconnect_attempts_total 7373
telemt_me_reconnect_success_total 6213
telemt_me_reader_eof_total 6587
telemt_me_idle_close_by_peer_total 6586
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 346094
telemt_me_route_drop_channel_closed_total 156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 782846
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 30
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4615
telemt_desync_full_logged_total 1410
telemt_desync_suppressed_total 3205
telemt_desync_frames_bucket_total{bucket="1_2"} 1534
telemt_desync_frames_bucket_total{bucket="3_10"} 1680
telemt_desync_frames_bucket_total{bucket="gt_10"} 1401
telemt_pool_swap_total 38
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 6325
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 6193
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 777201
telemt_user_connections_current{user="hello"} 1470
telemt_user_octets_from_client{user="hello"} 12078534852 (11.25 GB)
telemt_user_octets_to_client{user="hello"} 248444570432 (231.38 GB)
telemt_user_unique_ips_current{user="hello"} 521
telemt_user_unique_ips_recent_window{user="hello"} 210
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 45652.8 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2528520
telemt_connections_bad_total 159216
telemt_connections_current 4144
telemt_connections_me_current 4144
telemt_handshake_timeouts_total 54484
telemt_upstream_connect_attempt_total 8708
telemt_upstream_connect_success_total 8548
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 8708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4288
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8595
telemt_me_reconnect_success_total 6241
telemt_me_reader_eof_total 6629
telemt_me_idle_close_by_peer_total 6629
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 1165848
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2095201
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9583
telemt_desync_full_logged_total 3177
telemt_desync_suppressed_total 6406
telemt_desync_frames_bucket_total{bucket="1_2"} 1766
telemt_desync_frames_bucket_total{bucket="3_10"} 3774
telemt_desync_frames_bucket_total{bucket="gt_10"} 4043
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 6427
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 6219
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 2094872
telemt_user_connections_current{user="hello"} 4144
telemt_user_octets_from_client{user="hello"} 32468381148 (30.24 GB)
telemt_user_octets_to_client{user="hello"} 752177492296 (700.52 GB)
telemt_user_unique_ips_current{user="hello"} 1427
telemt_user_unique_ips_recent_window{user="hello"} 668
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 45649.4 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2181627
telemt_connections_bad_total 256598
telemt_connections_current 2906
telemt_connections_me_current 2906
telemt_handshake_timeouts_total 48459
telemt_upstream_connect_attempt_total 8121
telemt_upstream_connect_success_total 8121
telemt_upstream_connect_attempts_per_request{bucket="1"} 8121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3840
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5850
telemt_me_reconnect_success_total 5814
telemt_me_reader_eof_total 6155
telemt_me_idle_close_by_peer_total 6155
telemt_me_route_drop_no_conn_total 1339016
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1712174
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7355
telemt_desync_full_logged_total 2348
telemt_desync_suppressed_total 5007
telemt_desync_frames_bucket_total{bucket="1_2"} 1632
telemt_desync_frames_bucket_total{bucket="3_10"} 2718
telemt_desync_frames_bucket_total{bucket="gt_10"} 3005
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5917
telemt_me_writer_restored_same_endpoint_total 5798
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 103
telemt_user_connections_total{user="hello"} 1710544
telemt_user_connections_current{user="hello"} 2906
telemt_user_octets_from_client{user="hello"} 24547189540 (22.86 GB)
telemt_user_octets_to_client{user="hello"} 741965596532 (691.01 GB)
telemt_user_unique_ips_current{user="hello"} 991
telemt_user_unique_ips_recent_window{user="hello"} 420
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 45702.8 (12h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2161398
telemt_connections_bad_total 119540
telemt_connections_current 2900
telemt_connections_me_current 2900
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 56672
telemt_upstream_connect_attempt_total 16413
telemt_upstream_connect_success_total 16260
telemt_upstream_connect_fail_total 153
telemt_upstream_connect_attempts_per_request{bucket="1"} 16413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 153
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 9114
telemt_me_reconnect_success_total 5794
telemt_me_reader_eof_total 6157
telemt_me_idle_close_by_peer_total 6156
telemt_me_route_drop_no_conn_total 1099633
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1639690
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5966
telemt_desync_full_logged_total 2027
telemt_desync_suppressed_total 3939
telemt_desync_frames_bucket_total{bucket="1_2"} 1232
telemt_desync_frames_bucket_total{bucket="3_10"} 2321
telemt_desync_frames_bucket_total{bucket="gt_10"} 2413
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6212
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 5770
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 418
telemt_user_connections_total{user="hello"} 1645905
telemt_user_connections_current{user="hello"} 2900
telemt_user_octets_from_client{user="hello"} 18995523900 (17.69 GB)
telemt_user_octets_to_client{user="hello"} 474136622566 (441.57 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 977
telemt_user_unique_ips_recent_window{user="hello"} 440
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 45648.0 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2563886
telemt_connections_bad_total 571650
telemt_connections_current 3664
telemt_connections_me_current 3664
telemt_handshake_timeouts_total 51705
telemt_upstream_connect_attempt_total 8020
telemt_upstream_connect_success_total 7964
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 8020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4057
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3877
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 6868
telemt_me_reconnect_success_total 5668
telemt_me_reader_eof_total 6032
telemt_me_idle_close_by_peer_total 6031
telemt_me_route_drop_no_conn_total 954227
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1691030
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7562
telemt_desync_full_logged_total 2349
telemt_desync_suppressed_total 5213
telemt_desync_frames_bucket_total{bucket="1_2"} 1510
telemt_desync_frames_bucket_total{bucket="3_10"} 3274
telemt_desync_frames_bucket_total{bucket="gt_10"} 2778
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 5789
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5644
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 121
telemt_user_connections_total{user="hello"} 1690141
telemt_user_connections_current{user="hello"} 3664
telemt_user_octets_from_client{user="hello"} 29607039220 (27.57 GB)
telemt_user_octets_to_client{user="hello"} 704219082600 (655.86 GB)
telemt_user_unique_ips_current{user="hello"} 1223
telemt_user_unique_ips_recent_window{user="hello"} 542
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 45657.7 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 451507
telemt_connections_bad_total 18310
telemt_connections_current 854
telemt_connections_me_current 854
telemt_handshake_timeouts_total 3576
telemt_upstream_connect_attempt_total 11432
telemt_upstream_connect_success_total 11143
telemt_upstream_connect_fail_total 289
telemt_upstream_connect_attempts_per_request{bucket="1"} 11432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 289
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 14238
telemt_me_reconnect_success_total 8848
telemt_me_reader_eof_total 9384
telemt_me_idle_close_by_peer_total 9384
telemt_me_route_drop_no_conn_total 230295
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 407012
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 774
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 299
telemt_desync_frames_bucket_total{bucket="gt_10"} 298
telemt_pool_swap_total 22
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9091
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8818
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 243
telemt_user_connections_total{user="hello"} 406972
telemt_user_connections_current{user="hello"} 854
telemt_user_octets_from_client{user="hello"} 6487401084 (6.04 GB)
telemt_user_octets_to_client{user="hello"} 156622235808 (145.87 GB)
telemt_user_unique_ips_current{user="hello"} 335
telemt_user_unique_ips_recent_window{user="hello"} 145
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 45648.5 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1720303
telemt_connections_bad_total 138521
telemt_connections_current 3048
telemt_connections_me_current 3048
telemt_handshake_timeouts_total 69106
telemt_upstream_connect_attempt_total 9254
telemt_upstream_connect_success_total 9253
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 9254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4253
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 8301
telemt_me_reconnect_success_total 6946
telemt_me_reader_eof_total 7350
telemt_me_idle_close_by_peer_total 7349
telemt_me_route_drop_no_conn_total 680140
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1435548
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8155
telemt_desync_full_logged_total 2640
telemt_desync_suppressed_total 5515
telemt_desync_frames_bucket_total{bucket="1_2"} 1539
telemt_desync_frames_bucket_total{bucket="3_10"} 3065
telemt_desync_frames_bucket_total{bucket="gt_10"} 3551
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7074
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6931
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 128
telemt_user_connections_total{user="hello"} 1434337
telemt_user_connections_current{user="hello"} 3048
telemt_user_octets_from_client{user="hello"} 20224477996 (18.84 GB)
telemt_user_octets_to_client{user="hello"} 688289834124 (641.02 GB)
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 410
```