# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 16:09:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 68568.9 (19h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2416900
telemt_connections_bad_total 129012
telemt_connections_current 1611
telemt_connections_me_current 1611
telemt_handshake_timeouts_total 87113
telemt_upstream_connect_attempt_total 25392
telemt_upstream_connect_success_total 25391
telemt_upstream_connect_attempts_per_request{bucket="1"} 25391
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8840
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16484
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1027
telemt_me_reconnect_success_total 434
telemt_me_reader_eof_total 436
telemt_me_idle_close_by_peer_total 436
telemt_me_route_drop_no_conn_total 1954680
telemt_me_route_drop_channel_closed_total 794
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2056518
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 469
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 533
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 10016
telemt_desync_full_logged_total 3113
telemt_desync_suppressed_total 6903
telemt_desync_frames_bucket_total{bucket="1_2"} 2669
telemt_desync_frames_bucket_total{bucket="3_10"} 3761
telemt_desync_frames_bucket_total{bucket="gt_10"} 3586
telemt_pool_swap_total 76
telemt_pool_force_close_total 2318
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 448
telemt_me_draining_writers_reap_progress_total 23175
telemt_me_writer_removed_unexpected_total 423
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1686
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21698
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2271
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20857
telemt_me_writer_teardown_success_total{mode="normal"} 23384
telemt_me_writer_teardown_noop_total 23181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46565
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 210.789296
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46565
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 448
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 384
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2053132
telemt_user_connections_current{user="hello"} 1611
telemt_user_octets_from_client{user="hello"} 31170321916 (29.03 GB)
telemt_user_octets_to_client{user="hello"} 548343255624 (510.68 GB)
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 354
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 81934.6 (22h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3577616
telemt_connections_bad_total 326240
telemt_connections_current 1376
telemt_connections_me_current 1376
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 87630
telemt_upstream_connect_attempt_total 51682
telemt_upstream_connect_success_total 51055
telemt_upstream_connect_fail_total 555
telemt_upstream_connect_attempts_per_request{bucket="1"} 51610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 555
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6049
telemt_me_reconnect_success_total 2187
telemt_me_reader_eof_total 2130
telemt_me_idle_close_by_peer_total 2130
telemt_me_route_drop_no_conn_total 3525444
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2834197
telemt_me_endpoint_quarantine_total 659
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 630
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 11023
telemt_desync_full_logged_total 6145
telemt_desync_suppressed_total 4878
telemt_desync_frames_bucket_total{bucket="1_2"} 2574
telemt_desync_frames_bucket_total{bucket="3_10"} 4333
telemt_desync_frames_bucket_total{bucket="gt_10"} 4116
telemt_pool_swap_total 76
telemt_pool_force_close_total 2291
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 195
telemt_me_draining_writers_reap_progress_total 32653
telemt_me_writer_removed_unexpected_total 2085
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3945
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30799
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 356
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30362
telemt_me_writer_teardown_success_total{mode="normal"} 34744
telemt_me_writer_teardown_noop_total 32653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67382
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67395
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67397
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67397
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.174659
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67397
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 195
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1897
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 2845496
telemt_user_connections_current{user="hello"} 1376
telemt_user_octets_from_client{user="hello"} 35197159855 (32.78 GB)
telemt_user_octets_to_client{user="hello"} 628935288118 (585.74 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 757
telemt_user_unique_ips_recent_window{user="hello"} 347
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 156794.7 (43h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15266314
telemt_connections_bad_total 1418725
telemt_connections_current 1834
telemt_connections_me_current 1834
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 371422
telemt_upstream_connect_attempt_total 70925
telemt_upstream_connect_success_total 70830
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 70847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33480
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1673
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2615
telemt_me_reconnect_success_total 1346
telemt_me_reader_eof_total 1286
telemt_me_idle_close_by_peer_total 1284
telemt_me_route_drop_no_conn_total 13789692
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12201891
telemt_me_endpoint_quarantine_total 990
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1170
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 49630
telemt_desync_full_logged_total 15565
telemt_desync_suppressed_total 34065
telemt_desync_frames_bucket_total{bucket="1_2"} 11126
telemt_desync_frames_bucket_total{bucket="3_10"} 19407
telemt_desync_frames_bucket_total{bucket="gt_10"} 19097
telemt_pool_swap_total 169
telemt_pool_force_close_total 5765
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 937
telemt_me_draining_writers_reap_progress_total 51581
telemt_me_writer_removed_unexpected_total 1240
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4491
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47622
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45816
telemt_me_writer_teardown_success_total{mode="normal"} 52113
telemt_me_writer_teardown_noop_total 51631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 93655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96910
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 103174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 103705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 103735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 103736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 103740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 103742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 103744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 103744
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 295.979918
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 103744
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 937
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 1156
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 12203132
telemt_user_connections_current{user="hello"} 1834
telemt_user_octets_from_client{user="hello"} 171826995341 (160.03 GB)
telemt_user_octets_to_client{user="hello"} 3147942069955 (2.86 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 700
telemt_user_unique_ips_recent_window{user="hello"} 702
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 156796.2 (43h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11012327
telemt_connections_bad_total 1066141
telemt_connections_current 1331
telemt_connections_me_current 1331
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 326155
telemt_upstream_connect_attempt_total 83150
telemt_upstream_connect_success_total 81995
telemt_upstream_connect_fail_total 831
telemt_upstream_connect_attempts_per_request{bucket="1"} 82826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33380
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 831
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3928
telemt_me_reconnect_success_total 1593
telemt_me_reader_eof_total 1463
telemt_me_idle_close_by_peer_total 1463
telemt_me_route_drop_no_conn_total 4350607
telemt_me_route_drop_channel_closed_total 478
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8215611
telemt_me_endpoint_quarantine_total 988
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1187
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 36488
telemt_desync_full_logged_total 12264
telemt_desync_suppressed_total 24224
telemt_desync_frames_bucket_total{bucket="1_2"} 8933
telemt_desync_frames_bucket_total{bucket="3_10"} 14067
telemt_desync_frames_bucket_total{bucket="gt_10"} 13488
telemt_pool_swap_total 167
telemt_pool_force_close_total 5185
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 666
telemt_me_draining_writers_reap_progress_total 49891
telemt_me_writer_removed_unexpected_total 1493
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4606
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46637
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4709
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 476
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44706
telemt_me_writer_teardown_success_total{mode="normal"} 51243
telemt_me_writer_teardown_noop_total 49909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98928
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100736
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101144
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101152
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.260638
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101152
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 666
telemt_me_refill_failed_total 126
telemt_me_writer_restored_same_endpoint_total 1355
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 8154344
telemt_user_connections_current{user="hello"} 1331
telemt_user_octets_from_client{user="hello"} 204091671389 (190.08 GB)
telemt_user_octets_to_client{user="hello"} 3677958762010 (3.35 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 452
telemt_user_unique_ips_recent_window{user="hello"} 426
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 156760.1 (43h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10419250
telemt_connections_bad_total 896343
telemt_connections_current 1567
telemt_connections_me_current 1567
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 332609
telemt_upstream_connect_attempt_total 68323
telemt_upstream_connect_success_total 67389
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 67571
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31888
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1275
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2064
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4650
telemt_me_reconnect_success_total 1875
telemt_me_reader_eof_total 1632
telemt_me_idle_close_by_peer_total 1631
telemt_me_route_drop_no_conn_total 5121087
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7867370
telemt_me_endpoint_quarantine_total 1074
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1151
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 36016
telemt_desync_full_logged_total 11932
telemt_desync_suppressed_total 24084
telemt_desync_frames_bucket_total{bucket="1_2"} 9123
telemt_desync_frames_bucket_total{bucket="3_10"} 13762
telemt_desync_frames_bucket_total{bucket="gt_10"} 13131
telemt_pool_swap_total 164
telemt_pool_force_close_total 5107
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 50254
telemt_me_writer_removed_unexpected_total 1772
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5026
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46912
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4567
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 540
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45147
telemt_me_writer_teardown_success_total{mode="normal"} 51938
telemt_me_writer_teardown_noop_total 50325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102263
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.185154
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102263
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 147
telemt_me_writer_restored_same_endpoint_total 1625
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 139
telemt_user_connections_total{user="hello"} 7860358
telemt_user_connections_current{user="hello"} 1567
telemt_user_octets_from_client{user="hello"} 181309282701 (168.86 GB)
telemt_user_octets_to_client{user="hello"} 3266818452829 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 606
telemt_user_unique_ips_recent_window{user="hello"} 330
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 27039.9 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10090973
telemt_connections_bad_total 617296
telemt_connections_current 2209
telemt_connections_me_current 2209
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 182612
telemt_upstream_connect_attempt_total 35350
telemt_upstream_connect_success_total 33571
telemt_upstream_connect_fail_total 1251
telemt_upstream_connect_attempts_per_request{bucket="1"} 34822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5294
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1251
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5874
telemt_me_reconnect_success_total 698
telemt_me_reader_eof_total 440
telemt_me_idle_close_by_peer_total 440
telemt_me_route_drop_no_conn_total 24896231
telemt_me_route_drop_channel_closed_total 45
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8402436
telemt_me_endpoint_quarantine_total 168
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 210
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_writers_warm_current 11
telemt_desync_total 12988
telemt_desync_full_logged_total 3332
telemt_desync_suppressed_total 9656
telemt_desync_frames_bucket_total{bucket="1_2"} 2263
telemt_desync_frames_bucket_total{bucket="3_10"} 5285
telemt_desync_frames_bucket_total{bucket="gt_10"} 5440
telemt_pool_swap_total 25
telemt_pool_force_close_total 1013
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 360
telemt_me_draining_writers_reap_progress_total 7310
telemt_me_writer_removed_unexpected_total 601
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1230
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6645
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 735
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 278
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6297
telemt_me_writer_teardown_success_total{mode="normal"} 7875
telemt_me_writer_teardown_noop_total 7315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 12488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 15070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 15163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 15190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 15190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 15190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 15190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 15190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 15190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 15190
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 35.574757
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 15190
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 360
telemt_me_refill_failed_total 293
telemt_me_writer_restored_same_endpoint_total 474
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 8420615
telemt_user_connections_current{user="hello"} 2209
telemt_user_octets_from_client{user="hello"} 59106598550 (55.05 GB)
telemt_user_octets_to_client{user="hello"} 288786819264 (268.95 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 808
telemt_user_unique_ips_recent_window{user="hello"} 284
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 156766.4 (43h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10197274
telemt_connections_bad_total 851647
telemt_connections_current 1831
telemt_connections_me_current 1831
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 225859
telemt_upstream_connect_attempt_total 97108
telemt_upstream_connect_success_total 96118
telemt_upstream_connect_fail_total 843
telemt_upstream_connect_attempts_per_request{bucket="1"} 96961
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1303
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 843
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71826
telemt_me_reconnect_success_total 2606
telemt_me_reader_eof_total 2310
telemt_me_idle_close_by_peer_total 2309
telemt_me_route_drop_no_conn_total 5049376
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8042482
telemt_me_endpoint_quarantine_total 1062
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1168
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 41891
telemt_desync_full_logged_total 14298
telemt_desync_suppressed_total 27593
telemt_desync_frames_bucket_total{bucket="1_2"} 8520
telemt_desync_frames_bucket_total{bucket="3_10"} 16197
telemt_desync_frames_bucket_total{bucket="gt_10"} 17174
telemt_pool_swap_total 160
telemt_pool_force_close_total 4735
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 53372
telemt_me_writer_removed_unexpected_total 2354
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5714
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50032
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4050
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 685
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48637
telemt_me_writer_teardown_success_total{mode="normal"} 55746
telemt_me_writer_teardown_noop_total 53373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 108425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 108803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109119
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.408627
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109119
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 4268
telemt_me_writer_restored_same_endpoint_total 2188
telemt_me_writer_restored_fallback_total 44
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8046482
telemt_user_connections_current{user="hello"} 1831
telemt_user_octets_from_client{user="hello"} 182351557049 (169.83 GB)
telemt_user_octets_to_client{user="hello"} 3030772970024 (2.76 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 715
telemt_user_unique_ips_recent_window{user="hello"} 240
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 93602.6 (26h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10607753
telemt_connections_bad_total 394782
telemt_connections_current 1411
telemt_connections_me_current 1411
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4466317
telemt_upstream_connect_attempt_total 45091
telemt_upstream_connect_success_total 44763
telemt_upstream_connect_fail_total 319
telemt_upstream_connect_attempts_per_request{bucket="1"} 45082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 319
telemt_me_reconnect_attempts_total 48043
telemt_me_reconnect_success_total 1505
telemt_me_reader_eof_total 1168
telemt_me_idle_close_by_peer_total 1167
telemt_me_route_drop_no_conn_total 3906122
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5081130
telemt_me_endpoint_quarantine_total 609
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 701
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 27818
telemt_desync_full_logged_total 9399
telemt_desync_suppressed_total 18419
telemt_desync_frames_bucket_total{bucket="1_2"} 5587
telemt_desync_frames_bucket_total{bucket="3_10"} 10978
telemt_desync_frames_bucket_total{bucket="gt_10"} 11253
telemt_pool_swap_total 98
telemt_pool_force_close_total 3029
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 311
telemt_me_draining_writers_reap_progress_total 32142
telemt_me_writer_removed_unexpected_total 1231
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2893
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30510
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2610
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29113
telemt_me_writer_teardown_success_total{mode="normal"} 33403
telemt_me_writer_teardown_noop_total 32149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65552
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.763093
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65552
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 311
telemt_me_refill_failed_total 2705
telemt_me_writer_restored_same_endpoint_total 1339
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5074725
telemt_user_connections_current{user="hello"} 1411
telemt_user_octets_from_client{user="hello"} 109344925716 (101.84 GB)
telemt_user_octets_to_client{user="hello"} 1915455730202 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 583
telemt_user_unique_ips_recent_window{user="hello"} 207
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 74573.7 (20h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 991096
telemt_connections_bad_total 14476
telemt_connections_current 1127
telemt_connections_me_current 1127
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 19045
telemt_upstream_connect_attempt_total 36730
telemt_upstream_connect_success_total 36638
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 36714
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16624
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 516
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_reconnect_attempts_total 1648
telemt_me_reconnect_success_total 699
telemt_me_reader_eof_total 675
telemt_me_idle_close_by_peer_total 675
telemt_me_route_drop_no_conn_total 339386
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 877864
telemt_me_endpoint_quarantine_total 639
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 617
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 4892
telemt_desync_full_logged_total 1501
telemt_desync_suppressed_total 3391
telemt_desync_frames_bucket_total{bucket="1_2"} 1152
telemt_desync_frames_bucket_total{bucket="3_10"} 1953
telemt_desync_frames_bucket_total{bucket="gt_10"} 1787
telemt_pool_swap_total 79
telemt_pool_force_close_total 1996
telemt_me_writer_close_signal_drop_total 116
telemt_me_draining_writers_reap_progress_total 30390
telemt_me_writer_removed_unexpected_total 652
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2343
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28724
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1916
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28394
telemt_me_writer_teardown_success_total{mode="normal"} 31067
telemt_me_writer_teardown_noop_total 30393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60814
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 61460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 61460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 61460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 61460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 61460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 61460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 61460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 61460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 61460
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.540626
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 61460
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 116
telemt_me_refill_failed_total 52
telemt_me_writer_restored_same_endpoint_total 597
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 878877
telemt_user_connections_current{user="hello"} 1127
telemt_user_octets_from_client{user="hello"} 15835842605 (14.75 GB)
telemt_user_octets_to_client{user="hello"} 391875411127 (364.96 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 413
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 156771.1 (43h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12468786
telemt_connections_bad_total 1445096
telemt_connections_current 2065
telemt_connections_me_current 2065
telemt_handshake_timeouts_total 343398
telemt_upstream_connect_attempt_total 58892
telemt_upstream_connect_success_total 58663
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 58842
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29630
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_reconnect_attempts_total 2275
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1183
telemt_me_idle_close_by_peer_total 1183
telemt_me_route_drop_no_conn_total 4158577
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9426705
telemt_me_endpoint_quarantine_total 1064
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1170
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 38665
telemt_desync_full_logged_total 12619
telemt_desync_suppressed_total 26046
telemt_desync_frames_bucket_total{bucket="1_2"} 9199
telemt_desync_frames_bucket_total{bucket="3_10"} 14322
telemt_desync_frames_bucket_total{bucket="gt_10"} 15144
telemt_pool_swap_total 174
telemt_pool_force_close_total 4780
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 617
telemt_me_draining_writers_reap_progress_total 53036
telemt_me_writer_removed_unexpected_total 1136
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4339
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49866
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4607
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48256
telemt_me_writer_teardown_success_total{mode="normal"} 54205
telemt_me_writer_teardown_noop_total 53038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107243
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.005506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107243
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 617
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1067
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9396012
telemt_user_connections_current{user="hello"} 2065
telemt_user_octets_from_client{user="hello"} 184260206280 (171.61 GB)
telemt_user_octets_to_client{user="hello"} 4152015403600 (3.78 TB)
telemt_user_unique_ips_current{user="hello"} 751
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 156767.5 (43h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10811637
telemt_connections_bad_total 1209349
telemt_connections_current 1456
telemt_connections_me_current 1456
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 278676
telemt_upstream_connect_attempt_total 84610
telemt_upstream_connect_success_total 83975
telemt_upstream_connect_fail_total 550
telemt_upstream_connect_attempts_per_request{bucket="1"} 84525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 46190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34848
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 550
telemt_me_reconnect_attempts_total 8879
telemt_me_reconnect_success_total 2043
telemt_me_reader_eof_total 1907
telemt_me_idle_close_by_peer_total 1907
telemt_me_seq_mismatch_total 74
telemt_me_route_drop_no_conn_total 5406316
telemt_me_route_drop_channel_closed_total 347
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8356628
telemt_me_endpoint_quarantine_total 1188
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1170
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 38180
telemt_desync_full_logged_total 12332
telemt_desync_suppressed_total 25848
telemt_desync_frames_bucket_total{bucket="1_2"} 9483
telemt_desync_frames_bucket_total{bucket="3_10"} 14236
telemt_desync_frames_bucket_total{bucket="gt_10"} 14461
telemt_pool_swap_total 166
telemt_pool_force_close_total 4628
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 604
telemt_me_draining_writers_reap_progress_total 52417
telemt_me_writer_removed_unexpected_total 1933
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5436
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48982
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4189
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47789
telemt_me_writer_teardown_success_total{mode="normal"} 54418
telemt_me_writer_teardown_noop_total 52422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106840
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.481374
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106840
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 604
telemt_me_refill_failed_total 351
telemt_me_writer_restored_same_endpoint_total 1661
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 8362644
telemt_user_connections_current{user="hello"} 1456
telemt_user_octets_from_client{user="hello"} 147201798313 (137.09 GB)
telemt_user_octets_to_client{user="hello"} 3191168821683 (2.90 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 575
telemt_user_unique_ips_recent_window{user="hello"} 191
```