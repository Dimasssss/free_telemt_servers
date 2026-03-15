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

# Server Metrics 2026-03-15 13:11:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 53803.9 (14h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 239091
telemt_connections_bad_total 2229
telemt_handshake_timeouts_total 5146
telemt_upstream_connect_attempt_total 13512
telemt_upstream_connect_success_total 13442
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13512
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7439
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 14130
telemt_me_reconnect_success_total 10757
telemt_me_reader_eof_total 11495
telemt_me_idle_close_by_peer_total 11495
telemt_me_route_drop_no_conn_total 430612
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 283640
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1629
telemt_desync_full_logged_total 647
telemt_desync_suppressed_total 982
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 651
telemt_desync_frames_bucket_total{bucket="gt_10"} 699
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 10971
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10726
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 222746
telemt_user_connections_current{user="hello"} 426
telemt_user_octets_from_client{user="hello"} 4675670188 (4.35 GB)
telemt_user_octets_to_client{user="hello"} 200792814636 (187.00 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 53810.7 (14h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86751
telemt_connections_bad_total 2746
telemt_handshake_timeouts_total 7707
telemt_upstream_connect_attempt_total 14759
telemt_upstream_connect_success_total 14759
telemt_upstream_connect_attempts_per_request{bucket="1"} 14759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8308
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14385
telemt_me_reconnect_success_total 12044
telemt_me_reader_eof_total 12894
telemt_me_idle_close_by_peer_total 12894
telemt_me_route_drop_no_conn_total 37244
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73608
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
telemt_me_writer_removed_unexpected_total 12251
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 12028
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 207
telemt_user_connections_total{user="hello"} 73605
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 1471850716 (1.37 GB)
telemt_user_octets_to_client{user="hello"} 36216697704 (33.73 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 53802.9 (14h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 89471
telemt_connections_bad_total 1609
telemt_handshake_timeouts_total 2704
telemt_upstream_connect_attempt_total 15586
telemt_upstream_connect_success_total 15578
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6773
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8775
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 15011
telemt_me_reconnect_success_total 12862
telemt_me_reader_eof_total 13770
telemt_me_idle_close_by_peer_total 13770
telemt_me_route_drop_no_conn_total 34390
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81288
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
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 13052
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12854
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 81201
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 9909690260 (9.23 GB)
telemt_user_octets_to_client{user="hello"} 50018820648 (46.58 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 53802.7 (14h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122189
telemt_connections_bad_total 398
telemt_handshake_timeouts_total 774
telemt_upstream_connect_attempt_total 12620
telemt_upstream_connect_success_total 12618
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 12620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6044
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6533
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9991
telemt_me_reconnect_success_total 9932
telemt_me_reader_eof_total 10587
telemt_me_idle_close_by_peer_total 10587
telemt_me_route_drop_no_conn_total 48018
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 111359
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 327
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 136
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 10042
telemt_me_writer_restored_same_endpoint_total 9921
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 111278
telemt_user_connections_current{user="hello"} 217
telemt_user_octets_from_client{user="hello"} 1968197500 (1.83 GB)
telemt_user_octets_to_client{user="hello"} 58867302200 (54.82 GB)
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 28874.1 (8h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70600
telemt_connections_bad_total 20467
telemt_handshake_timeouts_total 1361
telemt_upstream_connect_attempt_total 9257
telemt_upstream_connect_success_total 9195
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 9257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 101978
telemt_me_reconnect_success_total 7557
telemt_me_reader_eof_total 7871
telemt_me_idle_close_by_peer_total 7871
telemt_me_route_drop_no_conn_total 23292
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47234
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
telemt_me_writer_removed_unexpected_total 7553
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 7453
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 47370
telemt_user_connections_current{user="hello"} 107
telemt_user_octets_from_client{user="hello"} 732586505 (698.65 MB)
telemt_user_octets_to_client{user="hello"} 19067091511 (17.76 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 53802.1 (14h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315761
telemt_connections_bad_total 47827
telemt_handshake_timeouts_total 2522
telemt_upstream_connect_attempt_total 11497
telemt_upstream_connect_success_total 11428
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5695
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 8789
telemt_me_reconnect_success_total 8728
telemt_me_reader_eof_total 9274
telemt_me_idle_close_by_peer_total 9274
telemt_me_route_drop_no_conn_total 141239
telemt_me_route_drop_channel_closed_total 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256103
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 233
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 163
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 73
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8809
telemt_me_writer_restored_same_endpoint_total 8701
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 254463
telemt_user_connections_current{user="hello"} 559
telemt_user_octets_from_client{user="hello"} 5193500144 (4.84 GB)
telemt_user_octets_to_client{user="hello"} 121164924432 (112.84 GB)
telemt_user_unique_ips_current{user="hello"} 225
telemt_user_unique_ips_recent_window{user="hello"} 67
```