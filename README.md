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

# Server Metrics 2026-03-15 05:42:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 26903.5 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68123
telemt_connections_bad_total 407
telemt_handshake_timeouts_total 1386
telemt_upstream_connect_attempt_total 6664
telemt_upstream_connect_success_total 6624
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 6664
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3609
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5307
telemt_me_reconnect_success_total 5288
telemt_me_reader_eof_total 5657
telemt_me_idle_close_by_peer_total 5657
telemt_me_route_drop_no_conn_total 20943
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63929
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 522
telemt_desync_full_logged_total 231
telemt_desync_suppressed_total 291
telemt_desync_frames_bucket_total{bucket="1_2"} 93
telemt_desync_frames_bucket_total{bucket="3_10"} 222
telemt_desync_frames_bucket_total{bucket="gt_10"} 207
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5327
telemt_me_writer_restored_same_endpoint_total 5257
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 63925
telemt_user_connections_current{user="hello"} 293
telemt_user_octets_from_client{user="hello"} 778282468 (742.23 MB)
telemt_user_octets_to_client{user="hello"} 21618024844 (20.13 GB)
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 26909.9 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24043
telemt_connections_bad_total 67
telemt_handshake_timeouts_total 108
telemt_upstream_connect_attempt_total 7329
telemt_upstream_connect_success_total 7329
telemt_upstream_connect_attempts_per_request{bucket="1"} 7329
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3210
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4113
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6007
telemt_me_reconnect_success_total 5981
telemt_me_reader_eof_total 6428
telemt_me_idle_close_by_peer_total 6428
telemt_me_route_drop_no_conn_total 11855
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22838
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 6036
telemt_me_writer_restored_same_endpoint_total 5965
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 22841
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 690899580 (658.89 MB)
telemt_user_octets_to_client{user="hello"} 8311536812 (7.74 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 26902.5 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31436
telemt_connections_bad_total 430
telemt_handshake_timeouts_total 1747
telemt_upstream_connect_attempt_total 7167
telemt_upstream_connect_success_total 7166
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7167
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3150
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5850
telemt_me_reconnect_success_total 5823
telemt_me_reader_eof_total 6290
telemt_me_idle_close_by_peer_total 6290
telemt_me_route_drop_no_conn_total 10771
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28242
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5875
telemt_me_writer_restored_same_endpoint_total 5819
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 28192
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 8748229724 (8.15 GB)
telemt_user_octets_to_client{user="hello"} 16774615776 (15.62 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 26902.2 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 31787
telemt_connections_bad_total 128
telemt_handshake_timeouts_total 187
telemt_upstream_connect_attempt_total 6344
telemt_upstream_connect_success_total 6343
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 6344
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3386
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5031
telemt_me_reconnect_success_total 5013
telemt_me_reader_eof_total 5363
telemt_me_idle_close_by_peer_total 5363
telemt_me_route_drop_no_conn_total 14671
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 29690
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 47
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 29
telemt_me_writer_removed_unexpected_total 5066
telemt_me_writer_restored_same_endpoint_total 5002
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 29609
telemt_user_connections_current{user="hello"} 242
telemt_user_octets_from_client{user="hello"} 584185108 (557.12 MB)
telemt_user_octets_to_client{user="hello"} 19264534448 (17.94 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 1973.7 (0h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2801
telemt_connections_bad_total 400
telemt_handshake_timeouts_total 13
telemt_upstream_connect_attempt_total 1109
telemt_upstream_connect_success_total 1084
telemt_upstream_connect_fail_total 25
telemt_upstream_connect_attempts_per_request{bucket="1"} 1109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 25
telemt_me_reconnect_attempts_total 95173
telemt_me_reconnect_success_total 786
telemt_me_reader_eof_total 727
telemt_me_idle_close_by_peer_total 727
telemt_me_route_drop_no_conn_total 705
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2194
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 704
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 682
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 2339
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 14310113 (13.65 MB)
telemt_user_octets_to_client{user="hello"} 1077424431 (1.00 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 26901.5 (7h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85009
telemt_connections_bad_total 1714
telemt_handshake_timeouts_total 384
telemt_upstream_connect_attempt_total 5958
telemt_upstream_connect_success_total 5925
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 5958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2961
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_reconnect_attempts_total 4606
telemt_me_reconnect_success_total 4586
telemt_me_reader_eof_total 4875
telemt_me_idle_close_by_peer_total 4875
telemt_me_route_drop_no_conn_total 46327
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81962
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 22
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 12
telemt_desync_frames_bucket_total{bucket="1_2"} 6
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4604
telemt_me_writer_restored_same_endpoint_total 4559
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 80524
telemt_user_connections_current{user="hello"} 286
telemt_user_octets_from_client{user="hello"} 2078312444 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 46301075420 (43.12 GB)
telemt_user_unique_ips_current{user="hello"} 142
telemt_user_unique_ips_recent_window{user="hello"} 51
```