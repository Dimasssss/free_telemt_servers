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

# Server Metrics 2026-03-13 06:47:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 83640.5 (23h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316907
telemt_connections_bad_total 3139
telemt_handshake_timeouts_total 6720
telemt_upstream_connect_attempt_total 21047
telemt_upstream_connect_success_total 20949
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 21047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1621
telemt_me_reconnect_attempts_total 20268
telemt_me_reconnect_success_total 16765
telemt_me_reader_eof_total 17923
telemt_me_idle_close_by_peer_total 17922
telemt_me_route_drop_no_conn_total 98679
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 268193
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
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 17055
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16749
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 268124
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 4544192772 (4.23 GB)
telemt_user_octets_to_client{user="hello"} 126957883108 (118.24 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 83533.5 (23h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 145217
telemt_connections_bad_total 1422
telemt_handshake_timeouts_total 1091
telemt_upstream_connect_attempt_total 43457
telemt_upstream_connect_success_total 42892
telemt_upstream_connect_fail_total 565
telemt_upstream_connect_attempts_per_request{bucket="1"} 43457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17070
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 565
telemt_me_keepalive_timeout_total 631
telemt_me_reconnect_attempts_total 71420
telemt_me_reconnect_success_total 22227
telemt_me_reader_eof_total 24440
telemt_me_idle_close_by_peer_total 24440
telemt_me_route_drop_no_conn_total 54803
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120946
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
telemt_me_writer_removed_unexpected_total 23939
telemt_me_refill_failed_total 1535
telemt_me_writer_restored_same_endpoint_total 22212
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1712
telemt_user_connections_total{user="hello"} 137441
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 1425634172 (1.33 GB)
telemt_user_octets_to_client{user="hello"} 44631841931 (41.57 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 83497.1 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176021
telemt_connections_bad_total 1912
telemt_handshake_timeouts_total 2872
telemt_upstream_connect_attempt_total 22823
telemt_upstream_connect_success_total 22821
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10524
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12274
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 19791
telemt_me_reconnect_success_total 18618
telemt_me_reader_eof_total 19957
telemt_me_idle_close_by_peer_total 19957
telemt_me_route_drop_no_conn_total 67791
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164691
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
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 18818
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18598
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 164618
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 2969655976 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 73188517464 (68.16 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 83472.7 (23h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 253690
telemt_connections_bad_total 13611
telemt_handshake_timeouts_total 1945
telemt_upstream_connect_attempt_total 35338
telemt_upstream_connect_success_total 25408
telemt_upstream_connect_fail_total 9930
telemt_upstream_connect_attempts_per_request{bucket="1"} 35338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12747
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12477
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9930
telemt_me_keepalive_timeout_total 3350
telemt_me_reconnect_attempts_total 69924
telemt_me_reconnect_success_total 18387
telemt_me_reader_eof_total 20565
telemt_me_idle_close_by_peer_total 20558
telemt_me_route_drop_no_conn_total 91758
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213850
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 643
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 456
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 20231
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18377
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1844
telemt_user_connections_total{user="hello"} 216582
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 4319794158 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 83637315249 (77.89 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 33644.2 (9h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39233
telemt_connections_bad_total 6982
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 11569
telemt_upstream_connect_success_total 11453
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 11569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6434
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 276
telemt_me_reconnect_attempts_total 10719
telemt_me_reconnect_success_total 9752
telemt_me_reader_eof_total 10404
telemt_me_idle_close_by_peer_total 10404
telemt_me_route_drop_no_conn_total 10986
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31067
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
telemt_me_writer_removed_unexpected_total 9868
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9734
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 31067
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 233792432 (222.96 MB)
telemt_user_octets_to_client{user="hello"} 10336707520 (9.63 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 83429.1 (23h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 428217
telemt_connections_bad_total 8091
telemt_handshake_timeouts_total 3249
telemt_upstream_connect_attempt_total 17776
telemt_upstream_connect_success_total 17679
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17776
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 1456
telemt_me_reconnect_attempts_total 17173
telemt_me_reconnect_success_total 13539
telemt_me_reader_eof_total 14540
telemt_me_idle_close_by_peer_total 14537
telemt_me_route_drop_no_conn_total 189823
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 414676
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
telemt_me_writer_removed_unexpected_total 13823
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13532
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 284
telemt_user_connections_total{user="hello"} 402911
telemt_user_connections_current{user="hello"} 376
telemt_user_octets_from_client{user="hello"} 6536315844 (6.09 GB)
telemt_user_octets_to_client{user="hello"} 234250313020 (218.16 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 53
```