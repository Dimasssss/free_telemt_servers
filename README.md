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

# Server Metrics 2026-03-19 01:12:03 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 12216.2 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139349
telemt_connections_bad_total 17227
telemt_connections_current 662
telemt_connections_me_current 662
telemt_handshake_timeouts_total 1516
telemt_upstream_connect_attempt_total 2482
telemt_upstream_connect_success_total 2439
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 2482
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1163
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1817
telemt_me_reconnect_success_total 1812
telemt_me_reader_eof_total 1880
telemt_me_idle_close_by_peer_total 1880
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 42491
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 114479
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 661
telemt_desync_full_logged_total 180
telemt_desync_suppressed_total 481
telemt_desync_frames_bucket_total{bucket="1_2"} 229
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 144
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1816
telemt_me_writer_restored_same_endpoint_total 1799
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 111711
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 1056879940 (1007.92 MB)
telemt_user_octets_to_client{user="hello"} 38983939348 (36.31 GB)
telemt_user_unique_ips_current{user="hello"} 282
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 12219.9 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 279676
telemt_connections_bad_total 19982
telemt_connections_current 1460
telemt_connections_me_current 1460
telemt_handshake_timeouts_total 3961
telemt_upstream_connect_attempt_total 2317
telemt_upstream_connect_success_total 2268
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 2317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 1640
telemt_me_reconnect_success_total 1635
telemt_me_reader_eof_total 1720
telemt_me_idle_close_by_peer_total 1720
telemt_me_seq_mismatch_total 3
telemt_me_route_drop_no_conn_total 83941
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 239506
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 899
telemt_desync_full_logged_total 305
telemt_desync_suppressed_total 594
telemt_desync_frames_bucket_total{bucket="1_2"} 209
telemt_desync_frames_bucket_total{bucket="3_10"} 320
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 12
telemt_me_writer_removed_unexpected_total 1663
telemt_me_writer_restored_same_endpoint_total 1622
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 239547
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 10986512168 (10.23 GB)
telemt_user_octets_to_client{user="hello"} 91670243948 (85.37 GB)
telemt_user_unique_ips_current{user="hello"} 602
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 12216.9 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 224094
telemt_connections_bad_total 39155
telemt_connections_current 978
telemt_connections_me_current 978
telemt_handshake_timeouts_total 5662
telemt_upstream_connect_attempt_total 2390
telemt_upstream_connect_success_total 2390
telemt_upstream_connect_attempts_per_request{bucket="1"} 2390
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1196
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1190
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1761
telemt_me_reconnect_success_total 1756
telemt_me_reader_eof_total 1842
telemt_me_idle_close_by_peer_total 1842
telemt_me_route_drop_no_conn_total 71598
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172482
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 830
telemt_desync_full_logged_total 304
telemt_desync_suppressed_total 526
telemt_desync_frames_bucket_total{bucket="1_2"} 163
telemt_desync_frames_bucket_total{bucket="3_10"} 323
telemt_desync_frames_bucket_total{bucket="gt_10"} 344
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1780
telemt_me_writer_restored_same_endpoint_total 1740
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 172482
telemt_user_connections_current{user="hello"} 978
telemt_user_octets_from_client{user="hello"} 2171587436 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 102547790444 (95.51 GB)
telemt_user_unique_ips_current{user="hello"} 456
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 12270.4 (3h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 242472
telemt_connections_bad_total 27540
telemt_connections_current 837
telemt_connections_me_current 837
telemt_handshake_timeouts_total 4384
telemt_upstream_connect_attempt_total 2253
telemt_upstream_connect_success_total 2253
telemt_upstream_connect_attempts_per_request{bucket="1"} 2253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 1625
telemt_me_reconnect_success_total 1619
telemt_me_reader_eof_total 1692
telemt_me_idle_close_by_peer_total 1692
telemt_me_route_drop_no_conn_total 77172
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 174763
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 493
telemt_desync_full_logged_total 177
telemt_desync_suppressed_total 316
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 199
telemt_desync_frames_bucket_total{bucket="gt_10"} 200
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1637
telemt_me_writer_restored_same_endpoint_total 1595
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 174681
telemt_user_connections_current{user="hello"} 837
telemt_user_octets_from_client{user="hello"} 1727250860 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 59944329716 (55.83 GB)
telemt_user_unique_ips_current{user="hello"} 382
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 12213.8 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 245765
telemt_connections_bad_total 14191
telemt_connections_current 1181
telemt_connections_me_current 1181
telemt_handshake_timeouts_total 8107
telemt_upstream_connect_attempt_total 2296
telemt_upstream_connect_success_total 2282
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 2295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1109
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1166
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 1655
telemt_me_reconnect_success_total 1644
telemt_me_reader_eof_total 1719
telemt_me_idle_close_by_peer_total 1719
telemt_me_route_drop_no_conn_total 76563
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 187658
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 724
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 438
telemt_desync_frames_bucket_total{bucket="1_2"} 190
telemt_desync_frames_bucket_total{bucket="3_10"} 254
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1651
telemt_me_writer_restored_same_endpoint_total 1620
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 187582
telemt_user_connections_current{user="hello"} 1181
telemt_user_octets_from_client{user="hello"} 2437501868 (2.27 GB)
telemt_user_octets_to_client{user="hello"} 110093790000 (102.53 GB)
telemt_user_unique_ips_current{user="hello"} 520
telemt_user_unique_ips_recent_window{user="hello"} 134
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 12225.3 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61510
telemt_connections_bad_total 9067
telemt_connections_current 335
telemt_connections_me_current 335
telemt_handshake_timeouts_total 176
telemt_upstream_connect_attempt_total 3564
telemt_upstream_connect_success_total 3454
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 3564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1820
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 4655
telemt_me_reconnect_success_total 2828
telemt_me_reader_eof_total 2951
telemt_me_idle_close_by_peer_total 2951
telemt_me_route_drop_no_conn_total 23178
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 50702
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 27
telemt_desync_full_logged_total 7
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2875
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2798
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 50702
telemt_user_connections_current{user="hello"} 335
telemt_user_octets_from_client{user="hello"} 751379224 (716.57 MB)
telemt_user_octets_to_client{user="hello"} 32198394572 (29.99 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 12216.0 (3h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174323
telemt_connections_bad_total 20392
telemt_connections_current 999
telemt_connections_me_current 999
telemt_handshake_timeouts_total 7727
telemt_upstream_connect_attempt_total 2599
telemt_upstream_connect_success_total 2599
telemt_upstream_connect_attempts_per_request{bucket="1"} 2599
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1368
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1229
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 1971
telemt_me_reconnect_success_total 1965
telemt_me_reader_eof_total 2059
telemt_me_idle_close_by_peer_total 2059
telemt_me_route_drop_no_conn_total 51815
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142176
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 946
telemt_desync_full_logged_total 378
telemt_desync_suppressed_total 568
telemt_desync_frames_bucket_total{bucket="1_2"} 172
telemt_desync_frames_bucket_total{bucket="3_10"} 377
telemt_desync_frames_bucket_total{bucket="gt_10"} 397
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 1987
telemt_me_writer_restored_same_endpoint_total 1950
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 142199
telemt_user_connections_current{user="hello"} 999
telemt_user_octets_from_client{user="hello"} 1448688376 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 73910042032 (68.83 GB)
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 71
```