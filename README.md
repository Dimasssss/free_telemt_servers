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

# Server Metrics 2026-03-14 07:17:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 171878.3 (47h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 659270
telemt_connections_bad_total 32379
telemt_handshake_timeouts_total 13063
telemt_upstream_connect_attempt_total 43762
telemt_upstream_connect_success_total 43542
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 43762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23488
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5683
telemt_me_reconnect_attempts_total 39306
telemt_me_reconnect_success_total 34614
telemt_me_reader_eof_total 36998
telemt_me_idle_close_by_peer_total 36997
telemt_me_route_drop_no_conn_total 217762
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 560908
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2100
telemt_desync_full_logged_total 719
telemt_desync_suppressed_total 1381
telemt_desync_frames_bucket_total{bucket="1_2"} 453
telemt_desync_frames_bucket_total{bucket="3_10"} 771
telemt_desync_frames_bucket_total{bucket="gt_10"} 876
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 35131
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34594
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 560792
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 16360495222 (15.24 GB)
telemt_user_octets_to_client{user="hello"} 269768409168 (251.24 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 171770.8 (47h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 332082
telemt_connections_bad_total 2327
telemt_handshake_timeouts_total 2549
telemt_upstream_connect_attempt_total 150497
telemt_upstream_connect_success_total 149228
telemt_upstream_connect_fail_total 1269
telemt_upstream_connect_attempts_per_request{bucket="1"} 150497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109973
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1269
telemt_me_keepalive_timeout_total 4020
telemt_me_reconnect_attempts_total 177970
telemt_me_reconnect_success_total 37380
telemt_me_reader_eof_total 42772
telemt_me_idle_close_by_peer_total 42772
telemt_me_route_drop_no_conn_total 109533
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211285
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 42121
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 37363
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4741
telemt_user_connections_total{user="hello"} 314393
telemt_user_connections_current{user="hello"} 121
telemt_user_octets_from_client{user="hello"} 3272019303 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 102826302315 (95.76 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 171734.8 (47h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 388120
telemt_connections_bad_total 3147
telemt_handshake_timeouts_total 35173
telemt_upstream_connect_attempt_total 45244
telemt_upstream_connect_success_total 45235
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20679
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24488
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3486
telemt_me_reconnect_attempts_total 37938
telemt_me_reconnect_success_total 36652
telemt_me_reader_eof_total 39413
telemt_me_idle_close_by_peer_total 39413
telemt_me_route_drop_no_conn_total 140058
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 336290
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 37096
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36631
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 444
telemt_user_connections_total{user="hello"} 336062
telemt_user_connections_current{user="hello"} 122
telemt_user_octets_from_client{user="hello"} 13523164640 (12.59 GB)
telemt_user_octets_to_client{user="hello"} 133686009604 (124.50 GB)
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 171710.0 (47h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 490166
telemt_connections_bad_total 16261
telemt_handshake_timeouts_total 4528
telemt_upstream_connect_attempt_total 75682
telemt_upstream_connect_success_total 65100
telemt_upstream_connect_fail_total 10581
telemt_upstream_connect_attempts_per_request{bucket="1"} 75681
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26368
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10581
telemt_me_keepalive_timeout_total 5407
telemt_me_reconnect_attempts_total 143589
telemt_me_reconnect_success_total 37527
telemt_me_reader_eof_total 42060
telemt_me_idle_close_by_peer_total 42052
telemt_me_route_drop_no_conn_total 177240
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 417291
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1776
telemt_desync_full_logged_total 530
telemt_desync_suppressed_total 1246
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 677
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 41269
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 37517
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3742
telemt_user_connections_total{user="hello"} 436169
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 9422977711 (8.78 GB)
telemt_user_octets_to_client{user="hello"} 178862486400 (166.58 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 121881.5 (33h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 198553
telemt_connections_bad_total 29386
telemt_handshake_timeouts_total 1736
telemt_upstream_connect_attempt_total 42999
telemt_upstream_connect_success_total 42589
telemt_upstream_connect_fail_total 410
telemt_upstream_connect_attempts_per_request{bucket="1"} 42999
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21333
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 410
telemt_me_keepalive_timeout_total 2527
telemt_me_reconnect_attempts_total 45064
telemt_me_reconnect_success_total 31632
telemt_me_reader_eof_total 33870
telemt_me_idle_close_by_peer_total 33870
telemt_me_route_drop_no_conn_total 59172
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157139
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 668
telemt_desync_full_logged_total 161
telemt_desync_suppressed_total 507
telemt_desync_frames_bucket_total{bucket="1_2"} 108
telemt_desync_frames_bucket_total{bucket="3_10"} 326
telemt_desync_frames_bucket_total{bucket="gt_10"} 234
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 32343
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31614
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 711
telemt_user_connections_total{user="hello"} 161888
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 2404564237 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 74980356375 (69.83 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 171666.2 (47h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 982570
telemt_connections_bad_total 36074
telemt_handshake_timeouts_total 26100
telemt_upstream_connect_attempt_total 35604
telemt_upstream_connect_success_total 35415
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 35604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18720
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 4720
telemt_me_reconnect_attempts_total 31612
telemt_me_reconnect_success_total 26933
telemt_me_reader_eof_total 28911
telemt_me_idle_close_by_peer_total 28908
telemt_me_route_drop_no_conn_total 462637
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 910565
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 27420
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26926
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 487
telemt_user_connections_total{user="hello"} 883211
telemt_user_connections_current{user="hello"} 437
telemt_user_octets_from_client{user="hello"} 15155353756 (14.11 GB)
telemt_user_octets_to_client{user="hello"} 445766007764 (415.15 GB)
telemt_user_unique_ips_current{user="hello"} 169
telemt_user_unique_ips_recent_window{user="hello"} 73
```