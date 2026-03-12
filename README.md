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

# Server Metrics 2026-03-12 20:35:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 46935.6 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229242
telemt_connections_bad_total 2651
telemt_handshake_timeouts_total 5097
telemt_upstream_connect_attempt_total 11767
telemt_upstream_connect_success_total 11713
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 11767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5166
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1448
telemt_me_reconnect_attempts_total 12759
telemt_me_reconnect_success_total 9297
telemt_me_reader_eof_total 9873
telemt_me_idle_close_by_peer_total 9872
telemt_me_route_drop_no_conn_total 70461
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 190495
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 665
telemt_desync_full_logged_total 247
telemt_desync_suppressed_total 418
telemt_desync_frames_bucket_total{bucket="1_2"} 121
telemt_desync_frames_bucket_total{bucket="3_10"} 251
telemt_desync_frames_bucket_total{bucket="gt_10"} 293
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 9513
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 9281
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 190272
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 3626909520 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 91911080740 (85.60 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 46828.5 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102737
telemt_connections_bad_total 536
telemt_handshake_timeouts_total 788
telemt_upstream_connect_attempt_total 28984
telemt_upstream_connect_success_total 28688
telemt_upstream_connect_fail_total 296
telemt_upstream_connect_attempts_per_request{bucket="1"} 28984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19713
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 491
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 296
telemt_me_keepalive_timeout_total 353
telemt_me_reconnect_attempts_total 49259
telemt_me_reconnect_success_total 9827
telemt_me_reader_eof_total 11257
telemt_me_idle_close_by_peer_total 11257
telemt_me_route_drop_no_conn_total 37321
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81140
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 11134
telemt_me_refill_failed_total 1231
telemt_me_writer_restored_same_endpoint_total 9812
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1307
telemt_user_connections_total{user="hello"} 97643
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 1078001972 (1.00 GB)
telemt_user_octets_to_client{user="hello"} 28534017543 (26.57 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 46791.8 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 128178
telemt_connections_bad_total 1536
telemt_handshake_timeouts_total 2200
telemt_upstream_connect_attempt_total 12943
telemt_upstream_connect_success_total 12942
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6775
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 296
telemt_me_reconnect_attempts_total 11687
telemt_me_reconnect_success_total 10550
telemt_me_reader_eof_total 11222
telemt_me_idle_close_by_peer_total 11222
telemt_me_route_drop_no_conn_total 48527
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119460
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 41
telemt_desync_full_logged_total 19
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 28
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 10689
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 10530
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 119430
telemt_user_connections_current{user="hello"} 73
telemt_user_octets_from_client{user="hello"} 2517036952 (2.34 GB)
telemt_user_octets_to_client{user="hello"} 57130555988 (53.21 GB)
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 46767.5 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 186590
telemt_connections_bad_total 13157
telemt_handshake_timeouts_total 1280
telemt_upstream_connect_attempt_total 23894
telemt_upstream_connect_success_total 14249
telemt_upstream_connect_fail_total 9645
telemt_upstream_connect_attempts_per_request{bucket="1"} 23894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7880
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6259
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 102
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9645
telemt_me_keepalive_timeout_total 2439
telemt_me_reconnect_attempts_total 40209
telemt_me_reconnect_success_total 9025
telemt_me_reader_eof_total 10279
telemt_me_idle_close_by_peer_total 10272
telemt_me_route_drop_no_conn_total 64302
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151130
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 491
telemt_desync_full_logged_total 142
telemt_desync_suppressed_total 349
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 182
telemt_desync_frames_bucket_total{bucket="gt_10"} 186
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 10151
telemt_me_refill_failed_total 971
telemt_me_writer_restored_same_endpoint_total 9015
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1126
telemt_user_connections_total{user="hello"} 153885
telemt_user_connections_current{user="hello"} 189
telemt_user_octets_from_client{user="hello"} 2875659874 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 60291272961 (56.15 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

Не удалось получить метрики для этого сервера.

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 46724.1 (12h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 293114
telemt_connections_bad_total 3149
telemt_handshake_timeouts_total 2244
telemt_upstream_connect_attempt_total 9760
telemt_upstream_connect_success_total 9710
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9760
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5170
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 488
telemt_me_reconnect_attempts_total 10973
telemt_me_reconnect_success_total 7366
telemt_me_reader_eof_total 7859
telemt_me_idle_close_by_peer_total 7858
telemt_me_route_drop_no_conn_total 135400
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 290535
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 285
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 177
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 107
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 7572
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 7359
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 206
telemt_user_connections_total{user="hello"} 278842
telemt_user_connections_current{user="hello"} 316
telemt_user_octets_from_client{user="hello"} 5083650760 (4.73 GB)
telemt_user_octets_to_client{user="hello"} 137283403840 (127.86 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 36
```