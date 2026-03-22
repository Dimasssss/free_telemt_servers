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

# Server Metrics 2026-03-22 02:25:45 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 19163.6 (5h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275935
telemt_connections_bad_total 18892
telemt_connections_current 828
telemt_connections_me_current 828
telemt_handshake_timeouts_total 15955
telemt_upstream_connect_attempt_total 8006
telemt_upstream_connect_success_total 8005
telemt_upstream_connect_attempts_per_request{bucket="1"} 8005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5091
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 250
telemt_me_reconnect_success_total 124
telemt_me_reader_eof_total 122
telemt_me_idle_close_by_peer_total 122
telemt_me_route_drop_no_conn_total 50774
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 226402
telemt_me_endpoint_quarantine_total 164
telemt_me_single_endpoint_shadow_rotate_total 164
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 45
telemt_desync_total 1988
telemt_desync_full_logged_total 544
telemt_desync_suppressed_total 1444
telemt_desync_frames_bucket_total{bucket="1_2"} 638
telemt_desync_frames_bucket_total{bucket="3_10"} 732
telemt_desync_frames_bucket_total{bucket="gt_10"} 618
telemt_pool_swap_total 21
telemt_pool_force_close_total 547
telemt_me_writer_close_signal_drop_total 37
telemt_me_draining_writers_reap_progress_total 7215
telemt_me_writer_removed_unexpected_total 122
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 505
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6822
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6668
telemt_me_writer_teardown_success_total{mode="normal"} 7327
telemt_me_writer_teardown_noop_total 7216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14543
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.858414
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14543
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 37
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 113
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 225985
telemt_user_connections_current{user="hello"} 828
telemt_user_octets_from_client{user="hello"} 2542913072 (2.37 GB)
telemt_user_octets_to_client{user="hello"} 82013260400 (76.38 GB)
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 32529.1 (9h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 776219
telemt_connections_bad_total 45993
telemt_connections_current 816
telemt_connections_me_current 816
telemt_handshake_timeouts_total 28619
telemt_upstream_connect_attempt_total 15100
telemt_upstream_connect_success_total 14858
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 15077
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6532
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_reconnect_attempts_total 1291
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 415
telemt_me_idle_close_by_peer_total 415
telemt_me_route_drop_no_conn_total 339614
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 616716
telemt_me_endpoint_quarantine_total 309
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 261
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_me_writers_active_current 41
telemt_desync_total 2686
telemt_desync_full_logged_total 1540
telemt_desync_suppressed_total 1146
telemt_desync_frames_bucket_total{bucket="1_2"} 569
telemt_desync_frames_bucket_total{bucket="3_10"} 1023
telemt_desync_frames_bucket_total{bucket="gt_10"} 1094
telemt_pool_swap_total 35
telemt_pool_force_close_total 933
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 13358
telemt_me_writer_removed_unexpected_total 394
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1121
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12639
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12425
telemt_me_writer_teardown_success_total{mode="normal"} 13760
telemt_me_writer_teardown_noop_total 13358
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27118
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.657692
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27118
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 346
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 615817
telemt_user_connections_current{user="hello"} 816
telemt_user_octets_from_client{user="hello"} 10080332308 (9.39 GB)
telemt_user_octets_to_client{user="hello"} 219211814888 (204.16 GB)
telemt_user_unique_ips_current{user="hello"} 517
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 107388.9 (29h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7711752
telemt_connections_bad_total 627005
telemt_connections_current 1302
telemt_connections_me_current 1302
telemt_handshake_timeouts_total 253682
telemt_upstream_connect_attempt_total 39761
telemt_upstream_connect_success_total 39687
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 39694
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17975
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1566
telemt_me_reconnect_success_total 806
telemt_me_reader_eof_total 815
telemt_me_idle_close_by_peer_total 815
telemt_me_route_drop_no_conn_total 4532392
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6246586
telemt_me_endpoint_quarantine_total 690
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 802
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26370
telemt_desync_full_logged_total 8727
telemt_desync_suppressed_total 17643
telemt_desync_frames_bucket_total{bucket="1_2"} 5686
telemt_desync_frames_bucket_total{bucket="3_10"} 10295
telemt_desync_frames_bucket_total{bucket="gt_10"} 10389
telemt_pool_swap_total 116
telemt_pool_force_close_total 3859
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 602
telemt_me_draining_writers_reap_progress_total 36275
telemt_me_writer_removed_unexpected_total 784
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3030
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33573
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3620
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32416
telemt_me_writer_teardown_success_total{mode="normal"} 36603
telemt_me_writer_teardown_noop_total 36319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72922
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 158.286456
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72922
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 602
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 716
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6238737
telemt_user_connections_current{user="hello"} 1302
telemt_user_octets_from_client{user="hello"} 106189392712 (98.90 GB)
telemt_user_octets_to_client{user="hello"} 2073235088404 (1.89 TB)
telemt_user_unique_ips_current{user="hello"} 683
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 107390.2 (29h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6361870
telemt_connections_bad_total 586267
telemt_connections_current 1434
telemt_connections_me_current 1434
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 210201
telemt_upstream_connect_attempt_total 43761
telemt_upstream_connect_success_total 43374
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 43564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21531
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21255
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1937
telemt_me_reconnect_success_total 867
telemt_me_reader_eof_total 839
telemt_me_idle_close_by_peer_total 839
telemt_me_route_drop_no_conn_total 2253465
telemt_me_route_drop_channel_closed_total 257
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4759527
telemt_me_endpoint_quarantine_total 671
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 825
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22534
telemt_desync_full_logged_total 7668
telemt_desync_suppressed_total 14866
telemt_desync_frames_bucket_total{bucket="1_2"} 5428
telemt_desync_frames_bucket_total{bucket="3_10"} 8743
telemt_desync_frames_bucket_total{bucket="gt_10"} 8363
telemt_pool_swap_total 117
telemt_pool_force_close_total 3492
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 34783
telemt_me_writer_removed_unexpected_total 824
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2926
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32618
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3279
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31291
telemt_me_writer_teardown_success_total{mode="normal"} 35544
telemt_me_writer_teardown_noop_total 34789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68571
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70333
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.280557
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70333
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4681711
telemt_user_connections_current{user="hello"} 1434
telemt_user_octets_from_client{user="hello"} 140031980921 (130.41 GB)
telemt_user_octets_to_client{user="hello"} 2205912316547 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 682
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 107354.4 (29h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6246807
telemt_connections_bad_total 547152
telemt_connections_current 1357
telemt_connections_me_current 1357
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 202336
telemt_upstream_connect_attempt_total 49971
telemt_upstream_connect_success_total 49605
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 49741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25483
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22592
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 461
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1069
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2022
telemt_me_reconnect_success_total 899
telemt_me_reader_eof_total 844
telemt_me_idle_close_by_peer_total 844
telemt_me_route_drop_no_conn_total 2147150
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4652455
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 804
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 22389
telemt_desync_full_logged_total 7525
telemt_desync_suppressed_total 14864
telemt_desync_frames_bucket_total{bucket="1_2"} 5464
telemt_desync_frames_bucket_total{bucket="3_10"} 8574
telemt_desync_frames_bucket_total{bucket="gt_10"} 8351
telemt_pool_swap_total 116
telemt_pool_force_close_total 3374
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 36019
telemt_me_writer_removed_unexpected_total 816
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2992
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33857
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32645
telemt_me_writer_teardown_success_total{mode="normal"} 36849
telemt_me_writer_teardown_noop_total 36031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72880
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 26.986168
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72880
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 780
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 4648082
telemt_user_connections_current{user="hello"} 1357
telemt_user_octets_from_client{user="hello"} 133475762351 (124.31 GB)
telemt_user_octets_to_client{user="hello"} 2125542716615 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 653
telemt_user_unique_ips_recent_window{user="hello"} 165
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 107393.4 (29h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20364313
telemt_connections_bad_total 1606068
telemt_connections_current 1872
telemt_connections_me_current 1872
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 602939
telemt_upstream_connect_attempt_total 195116
telemt_upstream_connect_success_total 177146
telemt_upstream_connect_fail_total 16227
telemt_upstream_connect_attempts_per_request{bucket="1"} 193373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8916
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16227
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64846
telemt_me_reconnect_success_total 2307
telemt_me_reader_eof_total 1442
telemt_me_idle_close_by_peer_total 1441
telemt_me_route_drop_no_conn_total 39502892
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16473841
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 846
telemt_me_single_endpoint_outage_enter_total 134
telemt_me_single_endpoint_outage_exit_total 134
telemt_me_single_endpoint_outage_reconnect_attempt_total 284
telemt_me_single_endpoint_outage_reconnect_success_total 69
telemt_me_single_endpoint_quarantine_bypass_total 284
telemt_me_single_endpoint_shadow_rotate_total 839
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 63
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
telemt_me_writers_active_current 45
telemt_desync_total 31897
telemt_desync_full_logged_total 9557
telemt_desync_suppressed_total 22340
telemt_desync_frames_bucket_total{bucket="1_2"} 6910
telemt_desync_frames_bucket_total{bucket="3_10"} 14157
telemt_desync_frames_bucket_total{bucket="gt_10"} 10830
telemt_pool_swap_total 111
telemt_pool_force_close_total 3626
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 793
telemt_me_draining_writers_reap_progress_total 33655
telemt_me_writer_removed_unexpected_total 2142
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4542
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30994
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30029
telemt_me_writer_teardown_success_total{mode="normal"} 35536
telemt_me_writer_teardown_noop_total 33681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64912
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67830
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69217
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.670839
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69217
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 793
telemt_me_refill_failed_total 3801
telemt_me_writer_restored_same_endpoint_total 1583
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 16603343
telemt_user_connections_current{user="hello"} 1872
telemt_user_octets_from_client{user="hello"} 215500846346 (200.70 GB)
telemt_user_octets_to_client{user="hello"} 1190476196755 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 936
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 107361.0 (29h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5999735
telemt_connections_bad_total 561886
telemt_connections_current 1020
telemt_connections_me_current 1020
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 125805
telemt_upstream_connect_attempt_total 58536
telemt_upstream_connect_success_total 57859
telemt_upstream_connect_fail_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 58439
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23644
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 580
telemt_me_reconnect_attempts_total 69644
telemt_me_reconnect_success_total 1782
telemt_me_reader_eof_total 1561
telemt_me_idle_close_by_peer_total 1560
telemt_me_route_drop_no_conn_total 2385909
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4682298
telemt_me_endpoint_quarantine_total 728
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 812
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 23312
telemt_desync_full_logged_total 8214
telemt_desync_suppressed_total 15098
telemt_desync_frames_bucket_total{bucket="1_2"} 4436
telemt_desync_frames_bucket_total{bucket="3_10"} 9026
telemt_desync_frames_bucket_total{bucket="gt_10"} 9850
telemt_pool_swap_total 111
telemt_pool_force_close_total 3201
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 37785
telemt_me_writer_removed_unexpected_total 1599
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3893
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35522
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34584
telemt_me_writer_teardown_success_total{mode="normal"} 39415
telemt_me_writer_teardown_noop_total 37786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77198
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77201
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.118777
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77201
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1493
telemt_me_writer_restored_fallback_total 34
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4675161
telemt_user_connections_current{user="hello"} 1020
telemt_user_octets_from_client{user="hello"} 124208246420 (115.68 GB)
telemt_user_octets_to_client{user="hello"} 1908369866362 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 510
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 44196.8 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3889801
telemt_connections_bad_total 141191
telemt_connections_current 1663
telemt_connections_me_current 1663
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1585221
telemt_upstream_connect_attempt_total 26990
telemt_upstream_connect_success_total 26815
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 26983
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9742
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_reconnect_attempts_total 45806
telemt_me_reconnect_success_total 953
telemt_me_reader_eof_total 635
telemt_me_idle_close_by_peer_total 635
telemt_me_route_drop_no_conn_total 1019445
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1908938
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 337
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 38
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10409
telemt_desync_full_logged_total 3592
telemt_desync_suppressed_total 6817
telemt_desync_frames_bucket_total{bucket="1_2"} 1862
telemt_desync_frames_bucket_total{bucket="3_10"} 3994
telemt_desync_frames_bucket_total{bucket="gt_10"} 4553
telemt_pool_swap_total 47
telemt_pool_force_close_total 1446
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 133
telemt_me_draining_writers_reap_progress_total 16050
telemt_me_writer_removed_unexpected_total 709
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1498
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15287
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1240
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14604
telemt_me_writer_teardown_success_total{mode="normal"} 16785
telemt_me_writer_teardown_noop_total 16052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32837
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.436418
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32837
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 133
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 854
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1912593
telemt_user_connections_current{user="hello"} 1663
telemt_user_octets_from_client{user="hello"} 53789767544 (50.10 GB)
telemt_user_octets_to_client{user="hello"} 814862272046 (758.90 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 842
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 25168.1 (6h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 192773
telemt_connections_bad_total 1639
telemt_connections_current 323
telemt_connections_me_current 323
telemt_handshake_timeouts_total 5306
telemt_upstream_connect_attempt_total 12042
telemt_upstream_connect_success_total 12014
telemt_upstream_connect_fail_total 26
telemt_upstream_connect_attempts_per_request{bucket="1"} 12040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5082
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 26
telemt_me_reconnect_attempts_total 242
telemt_me_reconnect_success_total 157
telemt_me_reader_eof_total 161
telemt_me_idle_close_by_peer_total 161
telemt_me_route_drop_no_conn_total 52731
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169846
telemt_me_endpoint_quarantine_total 247
telemt_me_single_endpoint_shadow_rotate_total 220
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_me_writers_active_current 45
telemt_desync_total 1012
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 756
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 251
telemt_pool_swap_total 27
telemt_pool_force_close_total 604
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 10850
telemt_me_writer_removed_unexpected_total 154
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 708
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10303
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 602
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10246
telemt_me_writer_teardown_success_total{mode="normal"} 11011
telemt_me_writer_teardown_noop_total 10850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 21665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 21833
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 21851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21861
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.968010
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21861
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 143
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 169536
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 3067240660 (2.86 GB)
telemt_user_octets_to_client{user="hello"} 102566283964 (95.52 GB)
telemt_user_unique_ips_current{user="hello"} 148
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 107365.8 (29h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7302638
telemt_connections_bad_total 740467
telemt_connections_current 1518
telemt_connections_me_current 1518
telemt_handshake_timeouts_total 208028
telemt_upstream_connect_attempt_total 42015
telemt_upstream_connect_success_total 41859
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 41978
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21050
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 1575
telemt_me_reconnect_success_total 841
telemt_me_reader_eof_total 824
telemt_me_idle_close_by_peer_total 824
telemt_me_route_drop_no_conn_total 2123731
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5464063
telemt_me_endpoint_quarantine_total 751
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 827
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 21434
telemt_desync_full_logged_total 7029
telemt_desync_suppressed_total 14405
telemt_desync_frames_bucket_total{bucket="1_2"} 5390
telemt_desync_frames_bucket_total{bucket="3_10"} 7749
telemt_desync_frames_bucket_total{bucket="gt_10"} 8295
telemt_pool_swap_total 119
telemt_pool_force_close_total 3191
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 37887
telemt_me_writer_removed_unexpected_total 795
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2987
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35714
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34696
telemt_me_writer_teardown_success_total{mode="normal"} 38701
telemt_me_writer_teardown_noop_total 37889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75236
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76502
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76590
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.639036
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76590
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 751
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5439107
telemt_user_connections_current{user="hello"} 1518
telemt_user_octets_from_client{user="hello"} 109347006008 (101.84 GB)
telemt_user_octets_to_client{user="hello"} 2535879415496 (2.31 TB)
telemt_user_unique_ips_current{user="hello"} 662
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 107361.9 (29h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6296051
telemt_connections_bad_total 622243
telemt_connections_current 1491
telemt_connections_me_current 1491
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 172293
telemt_upstream_connect_attempt_total 57808
telemt_upstream_connect_success_total 57374
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 57749
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33439
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22802
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_reconnect_attempts_total 5560
telemt_me_reconnect_success_total 1162
telemt_me_reader_eof_total 1048
telemt_me_idle_close_by_peer_total 1048
telemt_me_seq_mismatch_total 47
telemt_me_route_drop_no_conn_total 2176719
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4831009
telemt_me_endpoint_quarantine_total 850
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 823
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_active_current 45
telemt_desync_total 20048
telemt_desync_full_logged_total 6673
telemt_desync_suppressed_total 13375
telemt_desync_frames_bucket_total{bucket="1_2"} 5115
telemt_desync_frames_bucket_total{bucket="3_10"} 7309
telemt_desync_frames_bucket_total{bucket="gt_10"} 7624
telemt_pool_swap_total 117
telemt_pool_force_close_total 3153
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 380
telemt_me_draining_writers_reap_progress_total 36453
telemt_me_writer_removed_unexpected_total 1058
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3513
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34050
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2930
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33300
telemt_me_writer_teardown_success_total{mode="normal"} 37563
telemt_me_writer_teardown_noop_total 36457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74020
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.077372
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74020
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 380
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 907
telemt_me_writer_restored_fallback_total 61
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4834063
telemt_user_connections_current{user="hello"} 1491
telemt_user_octets_from_client{user="hello"} 91155358841 (84.90 GB)
telemt_user_octets_to_client{user="hello"} 2065325391592 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 664
telemt_user_unique_ips_recent_window{user="hello"} 175
```