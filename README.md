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

# Server Metrics 2026-03-15 13:00:59 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 53190.9 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 235105
telemt_connections_bad_total 2125
telemt_handshake_timeouts_total 4857
telemt_upstream_connect_attempt_total 13408
telemt_upstream_connect_success_total 13338
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5941
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 14034
telemt_me_reconnect_success_total 10661
telemt_me_reader_eof_total 11391
telemt_me_idle_close_by_peer_total 11391
telemt_me_route_drop_no_conn_total 429343
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 280186
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1603
telemt_desync_full_logged_total 639
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 271
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 691
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10875
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10630
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 219295
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 4547515484 (4.24 GB)
telemt_user_octets_to_client{user="hello"} 199200408156 (185.52 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 53197.6 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84923
telemt_connections_bad_total 2737
telemt_handshake_timeouts_total 7321
telemt_upstream_connect_attempt_total 14637
telemt_upstream_connect_success_total 14637
telemt_upstream_connect_attempts_per_request{bucket="1"} 14637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8243
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 121
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14263
telemt_me_reconnect_success_total 11923
telemt_me_reader_eof_total 12761
telemt_me_idle_close_by_peer_total 12761
telemt_me_route_drop_no_conn_total 36596
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72211
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 12127
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11907
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 204
telemt_user_connections_total{user="hello"} 72208
telemt_user_connections_current{user="hello"} 249
telemt_user_octets_from_client{user="hello"} 1453338224 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 35431887388 (33.00 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 53189.9 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87743
telemt_connections_bad_total 1301
telemt_handshake_timeouts_total 2686
telemt_upstream_connect_attempt_total 15455
telemt_upstream_connect_success_total 15447
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6716
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8701
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 14887
telemt_me_reconnect_success_total 12739
telemt_me_reader_eof_total 13634
telemt_me_idle_close_by_peer_total 13634
telemt_me_route_drop_no_conn_total 33750
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79935
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12928
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12731
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 79849
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 9895208564 (9.22 GB)
telemt_user_octets_to_client{user="hello"} 49607263628 (46.20 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 53189.5 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119810
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 767
telemt_upstream_connect_attempt_total 12432
telemt_upstream_connect_success_total 12431
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6435
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9821
telemt_me_reconnect_success_total 9764
telemt_me_reader_eof_total 10419
telemt_me_idle_close_by_peer_total 10419
telemt_me_route_drop_no_conn_total 47245
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 109192
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 308
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 215
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 123
telemt_desync_frames_bucket_total{bucket="gt_10"} 108
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9874
telemt_me_writer_restored_same_endpoint_total 9753
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 109112
telemt_user_connections_current{user="hello"} 251
telemt_user_octets_from_client{user="hello"} 1932557724 (1.80 GB)
telemt_user_octets_to_client{user="hello"} 58091648616 (54.10 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 28261.0 (7h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68138
telemt_connections_bad_total 19290
telemt_handshake_timeouts_total 1280
telemt_upstream_connect_attempt_total 9017
telemt_upstream_connect_success_total 8955
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 9017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4035
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4885
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 101768
telemt_me_reconnect_success_total 7347
telemt_me_reader_eof_total 7660
telemt_me_idle_close_by_peer_total 7660
telemt_me_route_drop_no_conn_total 22746
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 46028
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7343
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 7243
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 46163
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 680759089 (649.22 MB)
telemt_user_octets_to_client{user="hello"} 18184263179 (16.94 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 53189.3 (14h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 310404
telemt_connections_bad_total 47800
telemt_handshake_timeouts_total 2499
telemt_upstream_connect_attempt_total 11303
telemt_upstream_connect_success_total 11234
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11303
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5632
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5599
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 8607
telemt_me_reconnect_success_total 8548
telemt_me_reader_eof_total 9092
telemt_me_idle_close_by_peer_total 9092
telemt_me_route_drop_no_conn_total 138580
telemt_me_route_drop_channel_closed_total 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250964
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 220
telemt_desync_full_logged_total 69
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 70
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8626
telemt_me_writer_restored_same_endpoint_total 8521
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 249325
telemt_user_connections_current{user="hello"} 635
telemt_user_octets_from_client{user="hello"} 5151776184 (4.80 GB)
telemt_user_octets_to_client{user="hello"} 117854720128 (109.76 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 88
```