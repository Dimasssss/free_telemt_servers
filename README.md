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

# Server Metrics 2026-03-15 11:13:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 46759.8 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197934
telemt_connections_bad_total 1354
telemt_handshake_timeouts_total 4365
telemt_upstream_connect_attempt_total 11741
telemt_upstream_connect_success_total 11680
telemt_upstream_connect_fail_total 61
telemt_upstream_connect_attempts_per_request{bucket="1"} 11741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6465
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 11730
telemt_me_reconnect_success_total 9354
telemt_me_reader_eof_total 9989
telemt_me_idle_close_by_peer_total 9989
telemt_me_route_drop_no_conn_total 416904
telemt_me_route_drop_channel_closed_total 64
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 245696
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1452
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 877
telemt_desync_frames_bucket_total{bucket="1_2"} 238
telemt_desync_frames_bucket_total{bucket="3_10"} 577
telemt_desync_frames_bucket_total{bucket="gt_10"} 637
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9517
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 9323
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 184954
telemt_user_connections_current{user="hello"} 474
telemt_user_octets_from_client{user="hello"} 3465796212 (3.23 GB)
telemt_user_octets_to_client{user="hello"} 184842890840 (172.15 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 46767.6 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65519
telemt_connections_bad_total 2332
telemt_handshake_timeouts_total 3089
telemt_upstream_connect_attempt_total 12530
telemt_upstream_connect_success_total 12530
telemt_upstream_connect_attempts_per_request{bucket="1"} 12530
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7060
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12513
telemt_me_reconnect_success_total 10188
telemt_me_reader_eof_total 10941
telemt_me_idle_close_by_peer_total 10941
telemt_me_route_drop_no_conn_total 30871
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57963
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10372
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 10172
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 184
telemt_user_connections_total{user="hello"} 57962
telemt_user_connections_current{user="hello"} 224
telemt_user_octets_from_client{user="hello"} 1066313260 (1016.92 MB)
telemt_user_octets_to_client{user="hello"} 23932093384 (22.29 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 46759.6 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73444
telemt_connections_bad_total 1010
telemt_handshake_timeouts_total 2538
telemt_upstream_connect_attempt_total 13113
telemt_upstream_connect_success_total 13105
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 13113
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5616
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 11970
telemt_me_reconnect_success_total 10763
telemt_me_reader_eof_total 11536
telemt_me_idle_close_by_peer_total 11536
telemt_me_route_drop_no_conn_total 27935
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66722
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10899
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10755
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 66640
telemt_user_connections_current{user="hello"} 173
telemt_user_octets_from_client{user="hello"} 9419230556 (8.77 GB)
telemt_user_octets_to_client{user="hello"} 41102490872 (38.28 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 46759.0 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 96200
telemt_connections_bad_total 286
telemt_handshake_timeouts_total 645
telemt_upstream_connect_attempt_total 11017
telemt_upstream_connect_success_total 11016
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5730
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 8741
telemt_me_reconnect_success_total 8698
telemt_me_reader_eof_total 9286
telemt_me_idle_close_by_peer_total 9286
telemt_me_route_drop_no_conn_total 39110
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87935
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 201
telemt_desync_full_logged_total 62
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 83
telemt_desync_frames_bucket_total{bucket="gt_10"} 72
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 8790
telemt_me_writer_restored_same_endpoint_total 8687
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 87857
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 1667011024 (1.55 GB)
telemt_user_octets_to_client{user="hello"} 51950036136 (48.38 GB)
telemt_user_unique_ips_current{user="hello"} 78
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 21830.6 (6h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 39674
telemt_connections_bad_total 4540
telemt_handshake_timeouts_total 724
telemt_upstream_connect_attempt_total 7283
telemt_upstream_connect_success_total 7228
telemt_upstream_connect_fail_total 55
telemt_upstream_connect_attempts_per_request{bucket="1"} 7283
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3950
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 55
telemt_me_reconnect_attempts_total 100348
telemt_me_reconnect_success_total 5934
telemt_me_reader_eof_total 6151
telemt_me_idle_close_by_peer_total 6151
telemt_me_route_drop_no_conn_total 17124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33379
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 44
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 13
telemt_me_writer_removed_unexpected_total 5915
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 5830
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 33517
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 511541985 (487.84 MB)
telemt_user_octets_to_client{user="hello"} 13603224475 (12.67 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 46758.5 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257864
telemt_connections_bad_total 44949
telemt_handshake_timeouts_total 1979
telemt_upstream_connect_attempt_total 9960
telemt_upstream_connect_success_total 9900
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 9960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4993
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4905
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 7614
telemt_me_reconnect_success_total 7568
telemt_me_reader_eof_total 8063
telemt_me_idle_close_by_peer_total 8063
telemt_me_route_drop_no_conn_total 114220
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203346
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 32
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7627
telemt_me_writer_restored_same_endpoint_total 7541
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 201713
telemt_user_connections_current{user="hello"} 525
telemt_user_octets_from_client{user="hello"} 4675432564 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 99156962900 (92.35 GB)
telemt_user_unique_ips_current{user="hello"} 213
telemt_user_unique_ips_recent_window{user="hello"} 65
```