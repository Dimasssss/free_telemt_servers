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

# Server Metrics 2026-03-12 16:23:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 31787.5 (8h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167969
telemt_connections_bad_total 2028
telemt_handshake_timeouts_total 4792
telemt_upstream_connect_attempt_total 7870
telemt_upstream_connect_success_total 7840
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 7870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3488
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4345
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 298
telemt_me_reconnect_attempts_total 7323
telemt_me_reconnect_success_total 6191
telemt_me_reader_eof_total 6531
telemt_me_idle_close_by_peer_total 6530
telemt_me_route_drop_no_conn_total 48959
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144176
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 620
telemt_desync_full_logged_total 230
telemt_desync_suppressed_total 390
telemt_desync_frames_bucket_total{bucket="1_2"} 116
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 6284
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 6175
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 93
telemt_user_connections_total{user="hello"} 144134
telemt_user_connections_current{user="hello"} 331
telemt_user_octets_from_client{user="hello"} 2417272312 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 55655443456 (51.83 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 31680.6 (8h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70356
telemt_connections_bad_total 461
telemt_handshake_timeouts_total 588
telemt_upstream_connect_attempt_total 10211
telemt_upstream_connect_success_total 9998
telemt_upstream_connect_fail_total 213
telemt_upstream_connect_attempts_per_request{bucket="1"} 10211
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3961
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 213
telemt_me_keepalive_timeout_total 265
telemt_me_reconnect_attempts_total 29589
telemt_me_reconnect_success_total 8373
telemt_me_reader_eof_total 9198
telemt_me_idle_close_by_peer_total 9198
telemt_me_route_drop_no_conn_total 31150
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 66829
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 7
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 9096
telemt_me_refill_failed_total 662
telemt_me_writer_restored_same_endpoint_total 8358
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 723
telemt_user_connections_total{user="hello"} 66816
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 739606588 (705.34 MB)
telemt_user_octets_to_client{user="hello"} 18688548232 (17.41 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 31644.2 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95777
telemt_connections_bad_total 1488
telemt_handshake_timeouts_total 1962
telemt_upstream_connect_attempt_total 8724
telemt_upstream_connect_success_total 8724
telemt_upstream_connect_attempts_per_request{bucket="1"} 8724
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4232
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 165
telemt_me_reconnect_attempts_total 7108
telemt_me_reconnect_success_total 7045
telemt_me_reader_eof_total 7443
telemt_me_idle_close_by_peer_total 7443
telemt_me_route_drop_no_conn_total 35240
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 88384
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 26
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 13
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 15
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 7106
telemt_me_writer_restored_same_endpoint_total 7025
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 88358
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 2212985304 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 44209954260 (41.17 GB)
telemt_user_unique_ips_current{user="hello"} 65
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 31620.2 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 131267
telemt_connections_bad_total 13063
telemt_handshake_timeouts_total 993
telemt_upstream_connect_attempt_total 7208
telemt_upstream_connect_success_total 6989
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 7208
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3227
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3735
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_timeout_total 311
telemt_me_reconnect_attempts_total 29345
telemt_me_reconnect_success_total 5355
telemt_me_reader_eof_total 6238
telemt_me_idle_close_by_peer_total 6238
telemt_me_route_drop_no_conn_total 46671
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 110435
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 391
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 274
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 144
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6166
telemt_me_refill_failed_total 748
telemt_me_writer_restored_same_endpoint_total 5347
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 811
telemt_user_connections_total{user="hello"} 110315
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 2095435388 (1.95 GB)
telemt_user_octets_to_client{user="hello"} 46761443688 (43.55 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 31589.3 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 74752
telemt_connections_bad_total 6477
telemt_handshake_timeouts_total 1091
telemt_upstream_connect_attempt_total 37037
telemt_upstream_connect_success_total 36646
telemt_upstream_connect_fail_total 390
telemt_upstream_connect_attempts_per_request{bucket="1"} 37036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5530
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 390
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 42415
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4891
telemt_me_idle_close_by_peer_total 4891
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12737
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34123
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4917
telemt_me_refill_failed_total 1213
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1233
telemt_user_connections_total{user="hello"} 65477
telemt_user_connections_current{user="hello"} 94
telemt_user_octets_from_client{user="hello"} 586826557 (559.64 MB)
telemt_user_octets_to_client{user="hello"} 19617484972 (18.27 GB)
telemt_user_msgs_from_client{user="hello"} 501891
telemt_user_msgs_to_client{user="hello"} 1940310
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 31576.9 (8h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197822
telemt_connections_bad_total 955
telemt_handshake_timeouts_total 1556
telemt_upstream_connect_attempt_total 6785
telemt_upstream_connect_success_total 6752
telemt_upstream_connect_fail_total 33
telemt_upstream_connect_attempts_per_request{bucket="1"} 6785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3586
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33
telemt_me_keepalive_timeout_total 366
telemt_me_reconnect_attempts_total 6195
telemt_me_reconnect_success_total 5127
telemt_me_reader_eof_total 5401
telemt_me_idle_close_by_peer_total 5400
telemt_me_route_drop_no_conn_total 76649
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189101
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5227
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5120
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 189053
telemt_user_connections_current{user="hello"} 442
telemt_user_octets_from_client{user="hello"} 3571400656 (3.33 GB)
telemt_user_octets_to_client{user="hello"} 83339313688 (77.62 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 57
```