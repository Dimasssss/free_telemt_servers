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

# Server Metrics 2026-03-12 10:04:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 9080.7 (2h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47969
telemt_connections_bad_total 37
telemt_handshake_timeouts_total 2319
telemt_upstream_connect_attempt_total 2226
telemt_upstream_connect_success_total 2214
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 2225
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 1722
telemt_me_reconnect_success_total 1710
telemt_me_reader_eof_total 1761
telemt_me_idle_close_by_peer_total 1761
telemt_me_route_drop_no_conn_total 12648
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43030
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 151
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 64
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1716
telemt_me_writer_restored_same_endpoint_total 1694
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 43005
telemt_user_connections_current{user="hello"} 324
telemt_user_octets_from_client{user="hello"} 663023808 (632.31 MB)
telemt_user_octets_to_client{user="hello"} 12159862740 (11.32 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 8973.8 (2h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19761
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 177
telemt_upstream_connect_attempt_total 3191
telemt_upstream_connect_success_total 3131
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 3191
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 5462
telemt_me_reconnect_success_total 2671
telemt_me_reader_eof_total 2787
telemt_me_idle_close_by_peer_total 2787
telemt_me_route_drop_no_conn_total 7197
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18823
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 19
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 12
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 2757
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 2656
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 18821
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 209549212 (199.84 MB)
telemt_user_octets_to_client{user="hello"} 3728939984 (3.47 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 8937.6 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 27308
telemt_connections_bad_total 79
telemt_handshake_timeouts_total 199
telemt_upstream_connect_attempt_total 2323
telemt_upstream_connect_success_total 2323
telemt_upstream_connect_attempts_per_request{bucket="1"} 2323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1129
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 44
telemt_me_reconnect_attempts_total 1865
telemt_me_reconnect_success_total 1854
telemt_me_reader_eof_total 1920
telemt_me_idle_close_by_peer_total 1920
telemt_me_route_drop_no_conn_total 8853
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25368
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 5
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 1842
telemt_me_writer_restored_same_endpoint_total 1834
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_user_connections_total{user="hello"} 25363
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 267365676 (254.98 MB)
telemt_user_octets_to_client{user="hello"} 25324717028 (23.59 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 8913.2 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31230
telemt_connections_bad_total 1030
telemt_handshake_timeouts_total 168
telemt_upstream_connect_attempt_total 2505
telemt_upstream_connect_success_total 2443
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 2505
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1055
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1380
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 117
telemt_me_reconnect_attempts_total 2005
telemt_me_reconnect_success_total 1971
telemt_me_reader_eof_total 2052
telemt_me_idle_close_by_peer_total 2052
telemt_me_route_drop_no_conn_total 9055
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27707
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 40
telemt_desync_suppressed_total 79
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 2001
telemt_me_writer_restored_same_endpoint_total 1963
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 27706
telemt_user_connections_current{user="hello"} 186
telemt_user_octets_from_client{user="hello"} 713859268 (680.79 MB)
telemt_user_octets_to_client{user="hello"} 10402151872 (9.69 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 8882.6 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17313
telemt_connections_bad_total 1738
telemt_handshake_timeouts_total 244
telemt_upstream_connect_attempt_total 2567
telemt_upstream_connect_success_total 2468
telemt_upstream_connect_fail_total 99
telemt_upstream_connect_attempts_per_request{bucket="1"} 2567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 894
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 99
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 8413
telemt_me_reconnect_success_total 2001
telemt_me_reader_eof_total 2187
telemt_me_idle_close_by_peer_total 2187
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 4884
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14948
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 266
telemt_desync_full_logged_total 72
telemt_desync_suppressed_total 194
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 236
telemt_desync_frames_bucket_total{bucket="gt_10"} 26
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 2208
telemt_me_refill_failed_total 200
telemt_me_writer_restored_same_endpoint_total 1985
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 14946
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 73955668 (70.53 MB)
telemt_user_octets_to_client{user="hello"} 3982063584 (3.71 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 8869.5 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 43460
telemt_connections_bad_total 537
telemt_handshake_timeouts_total 582
telemt_upstream_connect_attempt_total 1625
telemt_upstream_connect_success_total 1615
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 827
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 1164
telemt_me_reconnect_success_total 1155
telemt_me_reader_eof_total 1205
telemt_me_idle_close_by_peer_total 1205
telemt_me_route_drop_no_conn_total 19284
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40713
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 29
telemt_desync_suppressed_total 67
telemt_desync_frames_bucket_total{bucket="1_2"} 35
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1170
telemt_me_writer_restored_same_endpoint_total 1148
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 40675
telemt_user_connections_current{user="hello"} 336
telemt_user_octets_from_client{user="hello"} 1732894048 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 25931463364 (24.15 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 45
```