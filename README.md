# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-20 03:46:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 37748.2 (10h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 695302
telemt_connections_bad_total 48901
telemt_connections_current 940
telemt_connections_me_current 940
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 15185
telemt_upstream_connect_attempt_total 7626
telemt_upstream_connect_success_total 7533
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 7626
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4591
telemt_me_reconnect_success_total 4551
telemt_me_reader_eof_total 4812
telemt_me_idle_close_by_peer_total 4811
telemt_me_route_drop_no_conn_total 196603
telemt_me_route_drop_channel_closed_total 62
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 551304
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2653
telemt_desync_full_logged_total 967
telemt_desync_suppressed_total 1686
telemt_desync_frames_bucket_total{bucket="1_2"} 534
telemt_desync_frames_bucket_total{bucket="3_10"} 979
telemt_desync_frames_bucket_total{bucket="gt_10"} 1140
telemt_pool_swap_total 41
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4591
telemt_me_writer_restored_same_endpoint_total 4538
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 552664
telemt_user_connections_current{user="hello"} 940
telemt_user_octets_from_client{user="hello"} 31293758968 (29.14 GB)
telemt_user_octets_to_client{user="hello"} 188219771837 (175.29 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 386
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 54203.8 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3278928
telemt_connections_bad_total 208307
telemt_connections_current 2239
telemt_connections_me_current 2239
telemt_handshake_timeouts_total 70666
telemt_upstream_connect_attempt_total 10518
telemt_upstream_connect_success_total 10330
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 10518
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4379
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10640
telemt_me_reconnect_success_total 6391
telemt_me_reader_eof_total 6839
telemt_me_idle_close_by_peer_total 6839
telemt_me_route_drop_no_conn_total 1558963
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2756651
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11673
telemt_desync_full_logged_total 3860
telemt_desync_suppressed_total 7813
telemt_desync_frames_bucket_total{bucket="1_2"} 2240
telemt_desync_frames_bucket_total{bucket="3_10"} 4553
telemt_desync_frames_bucket_total{bucket="gt_10"} 4880
telemt_pool_swap_total 48
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6599
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6336
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 2756359
telemt_user_connections_current{user="hello"} 2239
telemt_user_octets_from_client{user="hello"} 41950755370 (39.07 GB)
telemt_user_octets_to_client{user="hello"} 1031555515262 (960.71 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 894
telemt_user_unique_ips_recent_window{user="hello"} 274
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 54181.7 (15h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3115766
telemt_connections_bad_total 482800
telemt_connections_current 1636
telemt_connections_me_current 1636
telemt_handshake_timeouts_total 49599
telemt_upstream_connect_attempt_total 8875
telemt_upstream_connect_success_total 8810
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 8875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7037
telemt_me_reconnect_success_total 6100
telemt_me_reader_eof_total 6418
telemt_me_idle_close_by_peer_total 6417
telemt_me_route_drop_no_conn_total 1975313
telemt_me_route_drop_channel_closed_total 175
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2164345
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8014
telemt_desync_full_logged_total 2458
telemt_desync_suppressed_total 5556
telemt_desync_frames_bucket_total{bucket="1_2"} 1965
telemt_desync_frames_bucket_total{bucket="3_10"} 3043
telemt_desync_frames_bucket_total{bucket="gt_10"} 3006
telemt_pool_swap_total 54
telemt_me_writer_close_signal_drop_total 73
telemt_me_writer_removed_unexpected_total 6161
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6099
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 2159372
telemt_user_connections_current{user="hello"} 1636
telemt_user_octets_from_client{user="hello"} 32812127796 (30.56 GB)
telemt_user_octets_to_client{user="hello"} 845049162988 (787.01 GB)
telemt_user_unique_ips_current{user="hello"} 656
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 54169.5 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2800837
telemt_connections_bad_total 216978
telemt_connections_current 1665
telemt_connections_me_current 1665
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 33500
telemt_upstream_connect_attempt_total 58816
telemt_upstream_connect_success_total 54395
telemt_upstream_connect_fail_total 4421
telemt_upstream_connect_attempts_per_request{bucket="1"} 58816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45589
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8233
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 548
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4421
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9363
telemt_me_reconnect_success_total 6451
telemt_me_reader_eof_total 6722
telemt_me_idle_close_by_peer_total 6721
telemt_me_route_drop_no_conn_total 1929935
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2264720
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8752
telemt_desync_full_logged_total 2798
telemt_desync_suppressed_total 5954
telemt_desync_frames_bucket_total{bucket="1_2"} 2144
telemt_desync_frames_bucket_total{bucket="3_10"} 3198
telemt_desync_frames_bucket_total{bucket="gt_10"} 3410
telemt_pool_swap_total 41
telemt_me_writer_close_signal_drop_total 540
telemt_me_writer_removed_unexpected_total 7125
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6447
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 674
telemt_user_connections_total{user="hello"} 2308362
telemt_user_connections_current{user="hello"} 1665
telemt_user_octets_from_client{user="hello"} 36997005252 (34.46 GB)
telemt_user_octets_to_client{user="hello"} 673864186537 (627.58 GB)
telemt_user_msgs_from_client{user="hello"} 245686
telemt_user_msgs_to_client{user="hello"} 1753278
telemt_user_unique_ips_current{user="hello"} 638
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 107892.8 (29h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6514842
telemt_connections_bad_total 1131259
telemt_connections_current 1913
telemt_connections_me_current 1913
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 116653
telemt_upstream_connect_attempt_total 128804
telemt_upstream_connect_success_total 95512
telemt_upstream_connect_fail_total 33292
telemt_upstream_connect_attempts_per_request{bucket="1"} 128804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13115
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33292
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79512
telemt_me_reconnect_success_total 13838
telemt_me_reader_eof_total 14893
telemt_me_idle_close_by_peer_total 14879
telemt_me_route_drop_no_conn_total 2846757
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4590102
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19986
telemt_desync_full_logged_total 6355
telemt_desync_suppressed_total 13631
telemt_desync_frames_bucket_total{bucket="1_2"} 3533
telemt_desync_frames_bucket_total{bucket="3_10"} 8261
telemt_desync_frames_bucket_total{bucket="gt_10"} 8192
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 14156
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13813
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 318
telemt_user_connections_total{user="hello"} 4665172
telemt_user_connections_current{user="hello"} 1913
telemt_user_octets_from_client{user="hello"} 74125429172 (69.03 GB)
telemt_user_octets_to_client{user="hello"} 1816102671300 (1.65 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 723
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 54132.7 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1128072
telemt_connections_bad_total 94437
telemt_connections_current 700
telemt_connections_me_current 700
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13558
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 473063
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1422
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 878
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 599
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 965249
telemt_user_connections_current{user="hello"} 700
telemt_user_octets_from_client{user="hello"} 8006564795 (7.46 GB)
telemt_user_octets_to_client{user="hello"} 146603752878 (136.54 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 54134.3 (15h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2170413
telemt_connections_bad_total 130407
telemt_connections_current 1839
telemt_connections_me_current 1839
telemt_handshake_timeouts_total 41121
telemt_upstream_connect_attempt_total 9792
telemt_upstream_connect_success_total 9727
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5254
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4436
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7053
telemt_me_reconnect_success_total 7006
telemt_me_reader_eof_total 7398
telemt_me_idle_close_by_peer_total 7398
telemt_me_route_drop_no_conn_total 779397
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1845519
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9522
telemt_desync_full_logged_total 3070
telemt_desync_suppressed_total 6452
telemt_desync_frames_bucket_total{bucket="1_2"} 1848
telemt_desync_frames_bucket_total{bucket="3_10"} 3332
telemt_desync_frames_bucket_total{bucket="gt_10"} 4342
telemt_pool_swap_total 55
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 7104
telemt_me_writer_restored_same_endpoint_total 6989
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 1844617
telemt_user_connections_current{user="hello"} 1839
telemt_user_octets_from_client{user="hello"} 32044331932 (29.84 GB)
telemt_user_octets_to_client{user="hello"} 951492528380 (886.15 GB)
telemt_user_unique_ips_current{user="hello"} 665
telemt_user_unique_ips_recent_window{user="hello"} 197
```