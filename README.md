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

# Server Metrics 2026-03-14 14:25:37 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 4156.8 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21383
telemt_connections_bad_total 1375
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 1007
telemt_upstream_connect_success_total 1007
telemt_upstream_connect_attempts_per_request{bucket="1"} 1007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 761
telemt_me_reconnect_success_total 749
telemt_me_reader_eof_total 768
telemt_me_idle_close_by_peer_total 768
telemt_me_route_drop_no_conn_total 9792
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19439
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 28
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 10
telemt_desync_frames_bucket_total{bucket="3_10"} 17
telemt_desync_frames_bucket_total{bucket="gt_10"} 11
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 762
telemt_me_writer_restored_same_endpoint_total 731
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 19383
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 329328028 (314.07 MB)
telemt_user_octets_to_client{user="hello"} 7871881600 (7.33 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 4155.0 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9917
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 463
telemt_upstream_connect_attempt_total 1083
telemt_upstream_connect_success_total 1061
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 1083
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 610
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 832
telemt_me_reconnect_success_total 806
telemt_me_reader_eof_total 826
telemt_me_idle_close_by_peer_total 826
telemt_me_route_drop_no_conn_total 4428
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9138
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 824
telemt_me_writer_restored_same_endpoint_total 801
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 9121
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 97856348 (93.32 MB)
telemt_user_octets_to_client{user="hello"} 3054294876 (2.84 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 4159.4 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9570
telemt_connections_bad_total 48
telemt_handshake_timeouts_total 191
telemt_upstream_connect_attempt_total 2458
telemt_upstream_connect_success_total 2441
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 2458
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 40
telemt_me_reconnect_attempts_total 94497
telemt_me_reconnect_success_total 1871
telemt_me_reader_eof_total 1926
telemt_me_idle_close_by_peer_total 1926
telemt_me_route_drop_no_conn_total 3430
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8428
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 6
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_writer_removed_unexpected_total 1943
telemt_me_refill_failed_total 3006
telemt_me_writer_restored_same_endpoint_total 1833
telemt_me_writer_restored_fallback_total 38
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 8738
telemt_user_connections_current{user="hello"} 120
telemt_user_octets_from_client{user="hello"} 401877137 (383.26 MB)
telemt_user_octets_to_client{user="hello"} 4546596510 (4.23 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 4164.1 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13240
telemt_connections_bad_total 20
telemt_handshake_timeouts_total 89
telemt_upstream_connect_attempt_total 1017
telemt_upstream_connect_success_total 1013
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 1017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 451
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 554
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 770
telemt_me_reconnect_success_total 765
telemt_me_reader_eof_total 762
telemt_me_idle_close_by_peer_total 762
telemt_me_route_drop_no_conn_total 6754
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12603
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 161
telemt_desync_full_logged_total 41
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 761
telemt_me_writer_restored_same_endpoint_total 763
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_user_connections_total{user="hello"} 12487
telemt_user_connections_current{user="hello"} 213
telemt_user_octets_from_client{user="hello"} 164416132 (156.80 MB)
telemt_user_octets_to_client{user="hello"} 4175031676 (3.89 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 4157.3 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9265
telemt_connections_bad_total 890
telemt_handshake_timeouts_total 83
telemt_upstream_connect_attempt_total 1140
telemt_upstream_connect_success_total 1123
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 1140
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 493
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 630
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 3340
telemt_me_reconnect_success_total 868
telemt_me_reader_eof_total 920
telemt_me_idle_close_by_peer_total 920
telemt_me_route_drop_no_conn_total 3221
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7844
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 51
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 23
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_me_writer_removed_unexpected_total 939
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 864
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 7840
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 58469208 (55.76 MB)
telemt_user_octets_to_client{user="hello"} 1663208716 (1.55 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 4156.8 (1h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31914
telemt_connections_bad_total 36
telemt_handshake_timeouts_total 178
telemt_upstream_connect_attempt_total 962
telemt_upstream_connect_success_total 934
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 701
telemt_me_reconnect_success_total 676
telemt_me_reader_eof_total 664
telemt_me_idle_close_by_peer_total 664
telemt_me_route_drop_no_conn_total 15869
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29512
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1
telemt_desync_full_logged_total 1
telemt_desync_frames_bucket_total{bucket="3_10"} 1
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 673
telemt_me_writer_restored_same_endpoint_total 672
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 29427
telemt_user_connections_current{user="hello"} 513
telemt_user_octets_from_client{user="hello"} 584602100 (557.52 MB)
telemt_user_octets_to_client{user="hello"} 12289274480 (11.45 GB)
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 80
```