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

# Server Metrics 2026-03-13 10:28:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 96877.7 (26h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385616
telemt_connections_bad_total 3192
telemt_handshake_timeouts_total 8093
telemt_upstream_connect_attempt_total 24462
telemt_upstream_connect_success_total 24350
telemt_upstream_connect_fail_total 112
telemt_upstream_connect_attempts_per_request{bucket="1"} 24462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 112
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1765
telemt_me_reconnect_attempts_total 23008
telemt_me_reconnect_success_total 19488
telemt_me_reader_eof_total 20821
telemt_me_idle_close_by_peer_total 20820
telemt_me_route_drop_no_conn_total 120373
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 332208
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1074
telemt_desync_full_logged_total 397
telemt_desync_suppressed_total 677
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 396
telemt_desync_frames_bucket_total{bucket="gt_10"} 460
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 19801
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 19472
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 331912
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 5880966804 (5.48 GB)
telemt_user_octets_to_client{user="hello"} 143603327672 (133.74 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 96770.7 (26h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176676
telemt_connections_bad_total 1563
telemt_handshake_timeouts_total 1342
telemt_upstream_connect_attempt_total 47477
telemt_upstream_connect_success_total 46822
telemt_upstream_connect_fail_total 655
telemt_upstream_connect_attempts_per_request{bucket="1"} 47477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19383
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 655
telemt_me_keepalive_timeout_total 751
telemt_me_reconnect_attempts_total 85723
telemt_me_reconnect_success_total 25488
telemt_me_reader_eof_total 28121
telemt_me_idle_close_by_peer_total 28121
telemt_me_route_drop_no_conn_total 75643
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150076
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 20
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 27587
telemt_me_refill_failed_total 1879
telemt_me_writer_restored_same_endpoint_total 25472
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2099
telemt_user_connections_total{user="hello"} 166355
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 1725852336 (1.61 GB)
telemt_user_octets_to_client{user="hello"} 56008061527 (52.16 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 96734.5 (26h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 215021
telemt_connections_bad_total 2048
telemt_handshake_timeouts_total 4362
telemt_upstream_connect_attempt_total 26197
telemt_upstream_connect_success_total 26194
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 26197
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12070
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14099
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 752
telemt_me_reconnect_attempts_total 22503
telemt_me_reconnect_success_total 21305
telemt_me_reader_eof_total 22840
telemt_me_idle_close_by_peer_total 22840
telemt_me_route_drop_no_conn_total 80552
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200718
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 21537
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21285
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 200639
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 9190801128 (8.56 GB)
telemt_user_octets_to_client{user="hello"} 82444049624 (76.78 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 96709.9 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 303516
telemt_connections_bad_total 13675
telemt_handshake_timeouts_total 2230
telemt_upstream_connect_attempt_total 38931
telemt_upstream_connect_success_total 28903
telemt_upstream_connect_fail_total 10028
telemt_upstream_connect_attempts_per_request{bucket="1"} 38931
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14210
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10028
telemt_me_keepalive_timeout_total 3435
telemt_me_reconnect_attempts_total 83122
telemt_me_reconnect_success_total 21206
telemt_me_reader_eof_total 23787
telemt_me_idle_close_by_peer_total 23780
telemt_me_route_drop_no_conn_total 109510
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 260489
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 966
telemt_desync_full_logged_total 285
telemt_desync_suppressed_total 681
telemt_desync_frames_bucket_total{bucket="1_2"} 240
telemt_desync_frames_bucket_total{bucket="3_10"} 356
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23409
telemt_me_refill_failed_total 1930
telemt_me_writer_restored_same_endpoint_total 21196
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2203
telemt_user_connections_total{user="hello"} 263210
telemt_user_connections_current{user="hello"} 166
telemt_user_octets_from_client{user="hello"} 5666443562 (5.28 GB)
telemt_user_octets_to_client{user="hello"} 98512475777 (91.75 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 46881.4 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 63361
telemt_connections_bad_total 9379
telemt_handshake_timeouts_total 509
telemt_upstream_connect_attempt_total 16340
telemt_upstream_connect_success_total 16184
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 16340
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 414
telemt_me_reconnect_attempts_total 16064
telemt_me_reconnect_success_total 13834
telemt_me_reader_eof_total 14700
telemt_me_idle_close_by_peer_total 14700
telemt_me_route_drop_no_conn_total 19841
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51592
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 14027
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 13816
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 51587
telemt_user_connections_current{user="hello"} 96
telemt_user_octets_from_client{user="hello"} 473010904 (451.10 MB)
telemt_user_octets_to_client{user="hello"} 13725652204 (12.78 GB)
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 96666.3 (26h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531513
telemt_connections_bad_total 14508
telemt_handshake_timeouts_total 8390
telemt_upstream_connect_attempt_total 20662
telemt_upstream_connect_success_total 20555
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 20662
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10893
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1583
telemt_me_reconnect_attempts_total 20348
telemt_me_reconnect_success_total 15732
telemt_me_reader_eof_total 16891
telemt_me_idle_close_by_peer_total 16888
telemt_me_route_drop_no_conn_total 271924
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 516885
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 437
telemt_desync_full_logged_total 165
telemt_desync_suppressed_total 272
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 164
telemt_desync_frames_bucket_total{bucket="gt_10"} 167
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 16084
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 15725
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 352
telemt_user_connections_total{user="hello"} 489966
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 9107955276 (8.48 GB)
telemt_user_octets_to_client{user="hello"} 274525022836 (255.67 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 74
```