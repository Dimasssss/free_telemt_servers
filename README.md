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

# Server Metrics 2026-03-13 11:00:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 98828.3 (27h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 395505
telemt_connections_bad_total 3194
telemt_handshake_timeouts_total 8134
telemt_upstream_connect_attempt_total 24980
telemt_upstream_connect_success_total 24864
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 24980
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11208
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13608
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1801
telemt_me_reconnect_attempts_total 23435
telemt_me_reconnect_success_total 19913
telemt_me_reader_eof_total 21271
telemt_me_idle_close_by_peer_total 21270
telemt_me_route_drop_no_conn_total 124142
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341412
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1093
telemt_desync_full_logged_total 404
telemt_desync_suppressed_total 689
telemt_desync_frames_bucket_total{bucket="1_2"} 228
telemt_desync_frames_bucket_total{bucket="3_10"} 398
telemt_desync_frames_bucket_total{bucket="gt_10"} 467
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 20231
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19897
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 341097
telemt_user_connections_current{user="hello"} 413
telemt_user_octets_from_client{user="hello"} 6114651184 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 148538443828 (138.34 GB)
telemt_user_unique_ips_current{user="hello"} 113
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 98722.2 (27h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 181060
telemt_connections_bad_total 1605
telemt_handshake_timeouts_total 1381
telemt_upstream_connect_attempt_total 47828
telemt_upstream_connect_success_total 47160
telemt_upstream_connect_fail_total 668
telemt_upstream_connect_attempts_per_request{bucket="1"} 47828
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 668
telemt_me_keepalive_timeout_total 785
telemt_me_reconnect_attempts_total 88584
telemt_me_reconnect_success_total 25735
telemt_me_reader_eof_total 28455
telemt_me_idle_close_by_peer_total 28455
telemt_me_route_drop_no_conn_total 77177
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154278
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 21
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
telemt_me_writer_removed_unexpected_total 27920
telemt_me_refill_failed_total 1960
telemt_me_writer_restored_same_endpoint_total 25718
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2185
telemt_user_connections_total{user="hello"} 170557
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 1761245752 (1.64 GB)
telemt_user_octets_to_client{user="hello"} 57114448807 (53.19 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 98686.7 (27h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220973
telemt_connections_bad_total 2052
telemt_handshake_timeouts_total 4850
telemt_upstream_connect_attempt_total 26703
telemt_upstream_connect_success_total 26700
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 26703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14372
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 795
telemt_me_reconnect_attempts_total 22920
telemt_me_reconnect_success_total 21720
telemt_me_reader_eof_total 23275
telemt_me_idle_close_by_peer_total 23275
telemt_me_route_drop_no_conn_total 82479
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 205948
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 66
telemt_desync_full_logged_total 34
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 21957
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21700
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 205869
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 9242197496 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 89496511992 (83.35 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 98661.5 (27h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310202
telemt_connections_bad_total 13676
telemt_handshake_timeouts_total 2271
telemt_upstream_connect_attempt_total 39167
telemt_upstream_connect_success_total 29129
telemt_upstream_connect_fail_total 10038
telemt_upstream_connect_attempts_per_request{bucket="1"} 39167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14313
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10038
telemt_me_keepalive_timeout_total 3447
telemt_me_reconnect_attempts_total 86013
telemt_me_reconnect_success_total 21344
telemt_me_reader_eof_total 24011
telemt_me_idle_close_by_peer_total 24004
telemt_me_route_drop_no_conn_total 112128
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 266658
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 970
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 682
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23633
telemt_me_refill_failed_total 2016
telemt_me_writer_restored_same_endpoint_total 21334
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2289
telemt_user_connections_total{user="hello"} 269379
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 5714278958 (5.32 GB)
telemt_user_octets_to_client{user="hello"} 100110278569 (93.23 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 30
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 48833.0 (13h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67465
telemt_connections_bad_total 9743
telemt_handshake_timeouts_total 730
telemt_upstream_connect_attempt_total 17203
telemt_upstream_connect_success_total 17035
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 17203
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9538
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_timeout_total 439
telemt_me_reconnect_attempts_total 20355
telemt_me_reconnect_success_total 14509
telemt_me_reader_eof_total 15495
telemt_me_idle_close_by_peer_total 15495
telemt_me_route_drop_no_conn_total 21303
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54790
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 14822
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 14491
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 54850
telemt_user_connections_current{user="hello"} 55
telemt_user_octets_from_client{user="hello"} 492709372 (469.88 MB)
telemt_user_octets_to_client{user="hello"} 14923471292 (13.90 GB)
telemt_user_msgs_from_client{user="hello"} 217
telemt_user_msgs_to_client{user="hello"} 990
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 98618.0 (27h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 547704
telemt_connections_bad_total 14517
telemt_handshake_timeouts_total 10035
telemt_upstream_connect_attempt_total 21024
telemt_upstream_connect_success_total 20915
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 21024
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9802
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11088
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 1625
telemt_me_reconnect_attempts_total 20621
telemt_me_reconnect_success_total 16003
telemt_me_reader_eof_total 17182
telemt_me_idle_close_by_peer_total 17179
telemt_me_route_drop_no_conn_total 277131
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 530936
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 440
telemt_desync_full_logged_total 167
telemt_desync_suppressed_total 273
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 165
telemt_desync_frames_bucket_total{bucket="gt_10"} 169
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 16358
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 15996
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 355
telemt_user_connections_total{user="hello"} 504014
telemt_user_connections_current{user="hello"} 484
telemt_user_octets_from_client{user="hello"} 9204300132 (8.57 GB)
telemt_user_octets_to_client{user="hello"} 277536064532 (258.48 GB)
telemt_user_unique_ips_current{user="hello"} 174
telemt_user_unique_ips_recent_window{user="hello"} 69
```