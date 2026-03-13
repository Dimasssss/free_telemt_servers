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

# Server Metrics 2026-03-13 21:42:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 137349.9 (38h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 572351
telemt_connections_bad_total 16733
telemt_handshake_timeouts_total 12771
telemt_upstream_connect_attempt_total 34854
telemt_upstream_connect_success_total 34679
telemt_upstream_connect_fail_total 175
telemt_upstream_connect_attempts_per_request{bucket="1"} 34854
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18632
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 175
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5109
telemt_me_reconnect_attempts_total 32090
telemt_me_reconnect_success_total 27434
telemt_me_reader_eof_total 29291
telemt_me_idle_close_by_peer_total 29290
telemt_me_route_drop_no_conn_total 188804
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 492520
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1580
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1044
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 588
telemt_desync_frames_bucket_total{bucket="gt_10"} 652
telemt_pool_swap_total 122
telemt_me_writer_removed_unexpected_total 27887
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27418
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 453
telemt_user_connections_total{user="hello"} 492415
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 14763391370 (13.75 GB)
telemt_user_octets_to_client{user="hello"} 241841721260 (225.23 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 137242.3 (38h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 291055
telemt_connections_bad_total 2138
telemt_handshake_timeouts_total 1918
telemt_upstream_connect_attempt_total 138371
telemt_upstream_connect_success_total 137365
telemt_upstream_connect_fail_total 1006
telemt_upstream_connect_attempts_per_request{bucket="1"} 138371
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105350
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29606
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2409
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1006
telemt_me_keepalive_timeout_total 3671
telemt_me_reconnect_attempts_total 144269
telemt_me_reconnect_success_total 27194
telemt_me_reader_eof_total 31591
telemt_me_idle_close_by_peer_total 31591
telemt_me_route_drop_no_conn_total 86278
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 172839
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 35
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
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 31103
telemt_me_refill_failed_total 3653
telemt_me_writer_restored_same_endpoint_total 27177
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3909
telemt_user_connections_total{user="hello"} 275952
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 2854292155 (2.66 GB)
telemt_user_octets_to_client{user="hello"} 83905358127 (78.14 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 137206.5 (38h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338652
telemt_connections_bad_total 2658
telemt_handshake_timeouts_total 26923
telemt_upstream_connect_attempt_total 36516
telemt_upstream_connect_success_total 36511
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 36516
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19635
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2846
telemt_me_reconnect_attempts_total 30863
telemt_me_reconnect_success_total 29618
telemt_me_reader_eof_total 31774
telemt_me_idle_close_by_peer_total 31774
telemt_me_route_drop_no_conn_total 120650
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 297134
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
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
telemt_pool_swap_total 126
telemt_me_writer_removed_unexpected_total 29954
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 29598
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 336
telemt_user_connections_total{user="hello"} 297035
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 12324582500 (11.48 GB)
telemt_user_octets_to_client{user="hello"} 123345313160 (114.87 GB)
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 137181.7 (38h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443658
telemt_connections_bad_total 15257
telemt_handshake_timeouts_total 4225
telemt_upstream_connect_attempt_total 64046
telemt_upstream_connect_success_total 53691
telemt_upstream_connect_fail_total 10355
telemt_upstream_connect_attempts_per_request{bucket="1"} 64046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19890
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 303
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10355
telemt_me_keepalive_timeout_total 4769
telemt_me_reconnect_attempts_total 128898
telemt_me_reconnect_success_total 27807
telemt_me_reader_eof_total 31746
telemt_me_idle_close_by_peer_total 31739
telemt_me_route_drop_no_conn_total 154331
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 374283
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1589
telemt_desync_full_logged_total 470
telemt_desync_suppressed_total 1119
telemt_desync_frames_bucket_total{bucket="1_2"} 377
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 605
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 31317
telemt_me_refill_failed_total 3153
telemt_me_writer_restored_same_endpoint_total 27797
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3510
telemt_user_connections_total{user="hello"} 393140
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 8898477047 (8.29 GB)
telemt_user_octets_to_client{user="hello"} 149166507056 (138.92 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 87353.5 (24h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 148538
telemt_connections_bad_total 21915
telemt_handshake_timeouts_total 1524
telemt_upstream_connect_attempt_total 32626
telemt_upstream_connect_success_total 32316
telemt_upstream_connect_fail_total 310
telemt_upstream_connect_attempts_per_request{bucket="1"} 32626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 310
telemt_me_keepalive_timeout_total 1294
telemt_me_reconnect_attempts_total 36459
telemt_me_reconnect_success_total 23064
telemt_me_reader_eof_total 24700
telemt_me_idle_close_by_peer_total 24700
telemt_me_route_drop_no_conn_total 45605
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115565
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 611
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 468
telemt_desync_frames_bucket_total{bucket="1_2"} 92
telemt_desync_frames_bucket_total{bucket="3_10"} 302
telemt_desync_frames_bucket_total{bucket="gt_10"} 217
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 23700
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 23046
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 120459
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 1389495333 (1.29 GB)
telemt_user_octets_to_client{user="hello"} 56822783423 (52.92 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 137137.7 (38h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 832287
telemt_connections_bad_total 27126
telemt_handshake_timeouts_total 25080
telemt_upstream_connect_attempt_total 28238
telemt_upstream_connect_success_total 28090
telemt_upstream_connect_fail_total 148
telemt_upstream_connect_attempts_per_request{bucket="1"} 28238
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 148
telemt_me_keepalive_timeout_total 3119
telemt_me_reconnect_attempts_total 25932
telemt_me_reconnect_success_total 21281
telemt_me_reader_eof_total 22825
telemt_me_idle_close_by_peer_total 22822
telemt_me_route_drop_no_conn_total 396131
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 778794
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 21709
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21274
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 428
telemt_user_connections_total{user="hello"} 751655
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 13075969652 (12.18 GB)
telemt_user_octets_to_client{user="hello"} 374973256092 (349.22 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 35
```