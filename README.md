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

# Server Metrics 2026-03-22 02:30:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 19468.6 (5h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 280931
telemt_connections_bad_total 19300
telemt_connections_current 884
telemt_connections_me_current 884
telemt_handshake_timeouts_total 16276
telemt_upstream_connect_attempt_total 8130
telemt_upstream_connect_success_total 8129
telemt_upstream_connect_attempts_per_request{bucket="1"} 8129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5180
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 253
telemt_me_reconnect_success_total 128
telemt_me_reader_eof_total 125
telemt_me_idle_close_by_peer_total 125
telemt_me_route_drop_no_conn_total 51473
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 230309
telemt_me_endpoint_quarantine_total 164
telemt_me_single_endpoint_shadow_rotate_total 165
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
telemt_me_writers_active_current 47
telemt_desync_total 2043
telemt_desync_full_logged_total 559
telemt_desync_suppressed_total 1484
telemt_desync_frames_bucket_total{bucket="1_2"} 662
telemt_desync_frames_bucket_total{bucket="3_10"} 755
telemt_desync_frames_bucket_total{bucket="gt_10"} 626
telemt_pool_swap_total 21
telemt_pool_force_close_total 547
telemt_me_writer_close_signal_drop_total 37
telemt_me_draining_writers_reap_progress_total 7314
telemt_me_writer_removed_unexpected_total 125
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 510
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6919
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6767
telemt_me_writer_teardown_success_total{mode="normal"} 7429
telemt_me_writer_teardown_noop_total 7315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14744
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.865790
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14744
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 37
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 116
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 229938
telemt_user_connections_current{user="hello"} 884
telemt_user_octets_from_client{user="hello"} 2590039804 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 84482136792 (78.68 GB)
telemt_user_unique_ips_current{user="hello"} 375
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 32834.6 (9h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780531
telemt_connections_bad_total 46677
telemt_connections_current 440
telemt_connections_me_current 440
telemt_handshake_timeouts_total 28777
telemt_upstream_connect_attempt_total 15243
telemt_upstream_connect_success_total 15001
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 15220
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6603
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8355
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_reconnect_attempts_total 1295
telemt_me_reconnect_success_total 475
telemt_me_reader_eof_total 420
telemt_me_idle_close_by_peer_total 420
telemt_me_route_drop_no_conn_total 340001
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 619668
telemt_me_endpoint_quarantine_total 310
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 267
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
telemt_me_writers_active_current 43
telemt_desync_total 2696
telemt_desync_full_logged_total 1546
telemt_desync_suppressed_total 1150
telemt_desync_frames_bucket_total{bucket="1_2"} 574
telemt_desync_frames_bucket_total{bucket="3_10"} 1027
telemt_desync_frames_bucket_total{bucket="gt_10"} 1095
telemt_pool_swap_total 35
telemt_pool_force_close_total 959
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 13499
telemt_me_writer_removed_unexpected_total 398
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1135
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12771
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 937
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12540
telemt_me_writer_teardown_success_total{mode="normal"} 13906
telemt_me_writer_teardown_noop_total 13499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27405
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.703640
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27405
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 350
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 618763
telemt_user_connections_current{user="hello"} 440
telemt_user_octets_from_client{user="hello"} 10178709592 (9.48 GB)
telemt_user_octets_to_client{user="hello"} 220306115168 (205.18 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 107694.4 (29h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7722231
telemt_connections_bad_total 628086
telemt_connections_current 1672
telemt_connections_me_current 1672
telemt_handshake_timeouts_total 254148
telemt_upstream_connect_attempt_total 39884
telemt_upstream_connect_success_total 39810
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 39817
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18025
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21609
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 170
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1569
telemt_me_reconnect_success_total 809
telemt_me_reader_eof_total 818
telemt_me_idle_close_by_peer_total 818
telemt_me_route_drop_no_conn_total 4533424
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6252262
telemt_me_endpoint_quarantine_total 691
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 806
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
telemt_me_writers_active_current 45
telemt_desync_total 26394
telemt_desync_full_logged_total 8734
telemt_desync_suppressed_total 17660
telemt_desync_frames_bucket_total{bucket="1_2"} 5694
telemt_desync_frames_bucket_total{bucket="3_10"} 10305
telemt_desync_frames_bucket_total{bucket="gt_10"} 10395
telemt_pool_swap_total 116
telemt_pool_force_close_total 3859
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 602
telemt_me_draining_writers_reap_progress_total 36393
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3038
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33686
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3620
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32534
telemt_me_writer_teardown_success_total{mode="normal"} 36724
telemt_me_writer_teardown_noop_total 36437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66936
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72860
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73161
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 158.289682
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73161
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 602
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 719
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6244411
telemt_user_connections_current{user="hello"} 1672
telemt_user_octets_from_client{user="hello"} 106229468312 (98.93 GB)
telemt_user_octets_to_client{user="hello"} 2075453668772 (1.89 TB)
telemt_user_unique_ips_current{user="hello"} 852
telemt_user_unique_ips_recent_window{user="hello"} 194
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 107695.8 (29h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6369825
telemt_connections_bad_total 586556
telemt_connections_current 1597
telemt_connections_me_current 1597
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 210659
telemt_upstream_connect_attempt_total 43888
telemt_upstream_connect_success_total 43501
telemt_upstream_connect_fail_total 190
telemt_upstream_connect_attempts_per_request{bucket="1"} 43691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21597
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21316
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 190
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1940
telemt_me_reconnect_success_total 870
telemt_me_reader_eof_total 842
telemt_me_idle_close_by_peer_total 842
telemt_me_route_drop_no_conn_total 2254637
telemt_me_route_drop_channel_closed_total 259
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4764626
telemt_me_endpoint_quarantine_total 671
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 829
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22535
telemt_desync_full_logged_total 7669
telemt_desync_suppressed_total 14866
telemt_desync_frames_bucket_total{bucket="1_2"} 5428
telemt_desync_frames_bucket_total{bucket="3_10"} 8744
telemt_desync_frames_bucket_total{bucket="gt_10"} 8363
telemt_pool_swap_total 117
telemt_pool_force_close_total 3492
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 359
telemt_me_draining_writers_reap_progress_total 34898
telemt_me_writer_removed_unexpected_total 827
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2931
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32731
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3279
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31406
telemt_me_writer_teardown_success_total{mode="normal"} 35662
telemt_me_writer_teardown_noop_total 34904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70566
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.282231
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70566
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 359
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4686813
telemt_user_connections_current{user="hello"} 1597
telemt_user_octets_from_client{user="hello"} 140107598357 (130.49 GB)
telemt_user_octets_to_client{user="hello"} 2209367809803 (2.01 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 764
telemt_user_unique_ips_recent_window{user="hello"} 168
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 107661.3 (29h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6254915
telemt_connections_bad_total 547272
telemt_connections_current 1482
telemt_connections_me_current 1482
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 202539
telemt_upstream_connect_attempt_total 50054
telemt_upstream_connect_success_total 49688
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 49824
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25499
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22658
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 462
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1069
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2022
telemt_me_reconnect_success_total 899
telemt_me_reader_eof_total 844
telemt_me_idle_close_by_peer_total 844
telemt_me_route_drop_no_conn_total 2147984
telemt_me_route_drop_channel_closed_total 120
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4657071
telemt_me_endpoint_quarantine_total 750
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 806
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
telemt_me_writers_active_current 44
telemt_desync_total 22397
telemt_desync_full_logged_total 7533
telemt_desync_suppressed_total 14864
telemt_desync_frames_bucket_total{bucket="1_2"} 5467
telemt_desync_frames_bucket_total{bucket="3_10"} 8577
telemt_desync_frames_bucket_total{bucket="gt_10"} 8353
telemt_pool_swap_total 116
telemt_pool_force_close_total 3374
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 36101
telemt_me_writer_removed_unexpected_total 816
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2996
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33935
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32727
telemt_me_writer_teardown_success_total{mode="normal"} 36931
telemt_me_writer_teardown_noop_total 36113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72999
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 73026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 73044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 73044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 73044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 73044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 73044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 73044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 73044
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 26.987870
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 73044
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 62
telemt_me_writer_restored_same_endpoint_total 780
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 4652698
telemt_user_connections_current{user="hello"} 1482
telemt_user_octets_from_client{user="hello"} 133540069287 (124.37 GB)
telemt_user_octets_to_client{user="hello"} 2128096963063 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 107699.3 (29h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20376932
telemt_connections_bad_total 1610710
telemt_connections_current 2152
telemt_connections_me_current 2152
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 604016
telemt_upstream_connect_attempt_total 195223
telemt_upstream_connect_success_total 177250
telemt_upstream_connect_fail_total 16227
telemt_upstream_connect_attempts_per_request{bucket="1"} 193477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 124797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8917
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16227
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64846
telemt_me_reconnect_success_total 2307
telemt_me_reader_eof_total 1442
telemt_me_idle_close_by_peer_total 1441
telemt_me_route_drop_no_conn_total 39504247
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16480579
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 847
telemt_me_single_endpoint_outage_enter_total 134
telemt_me_single_endpoint_outage_exit_total 134
telemt_me_single_endpoint_outage_reconnect_attempt_total 284
telemt_me_single_endpoint_outage_reconnect_success_total 69
telemt_me_single_endpoint_quarantine_bypass_total 284
telemt_me_single_endpoint_shadow_rotate_total 843
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
telemt_me_writers_active_current 46
telemt_desync_total 31914
telemt_desync_full_logged_total 9564
telemt_desync_suppressed_total 22350
telemt_desync_frames_bucket_total{bucket="1_2"} 6914
telemt_desync_frames_bucket_total{bucket="3_10"} 14166
telemt_desync_frames_bucket_total{bucket="gt_10"} 10834
telemt_pool_swap_total 111
telemt_pool_force_close_total 3626
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 793
telemt_me_draining_writers_reap_progress_total 33757
telemt_me_writer_removed_unexpected_total 2142
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4543
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31095
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 523
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30131
telemt_me_writer_teardown_success_total{mode="normal"} 35638
telemt_me_writer_teardown_noop_total 33783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69421
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 214.672197
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69421
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 793
telemt_me_refill_failed_total 3801
telemt_me_writer_restored_same_endpoint_total 1583
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 538
telemt_user_connections_total{user="hello"} 16610080
telemt_user_connections_current{user="hello"} 2152
telemt_user_octets_from_client{user="hello"} 216468097314 (201.60 GB)
telemt_user_octets_to_client{user="hello"} 1192417293723 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 373576
telemt_user_msgs_to_client{user="hello"} 663916
telemt_user_unique_ips_current{user="hello"} 1031
telemt_user_unique_ips_recent_window{user="hello"} 244
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 107666.7 (29h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6006542
telemt_connections_bad_total 562975
telemt_connections_current 1443
telemt_connections_me_current 1443
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 126100
telemt_upstream_connect_attempt_total 58639
telemt_upstream_connect_success_total 57962
telemt_upstream_connect_fail_total 580
telemt_upstream_connect_attempts_per_request{bucket="1"} 58542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23696
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 350
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 580
telemt_me_reconnect_attempts_total 69644
telemt_me_reconnect_success_total 1782
telemt_me_reader_eof_total 1561
telemt_me_idle_close_by_peer_total 1560
telemt_me_route_drop_no_conn_total 2386645
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4687100
telemt_me_endpoint_quarantine_total 729
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 816
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
telemt_desync_total 23333
telemt_desync_full_logged_total 8220
telemt_desync_suppressed_total 15113
telemt_desync_frames_bucket_total{bucket="1_2"} 4442
telemt_desync_frames_bucket_total{bucket="3_10"} 9038
telemt_desync_frames_bucket_total{bucket="gt_10"} 9853
telemt_pool_swap_total 111
telemt_pool_force_close_total 3201
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 37888
telemt_me_writer_removed_unexpected_total 1599
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3900
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35618
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34687
telemt_me_writer_teardown_success_total{mode="normal"} 39518
telemt_me_writer_teardown_noop_total 37889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 77375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77407
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77407
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.119512
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77407
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1493
telemt_me_writer_restored_fallback_total 34
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 4679963
telemt_user_connections_current{user="hello"} 1443
telemt_user_octets_from_client{user="hello"} 124253337464 (115.72 GB)
telemt_user_octets_to_client{user="hello"} 1910128044698 (1.74 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 806
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 44502.5 (12h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3899220
telemt_connections_bad_total 141487
telemt_connections_current 1213
telemt_connections_me_current 1213
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1588107
telemt_upstream_connect_attempt_total 27163
telemt_upstream_connect_success_total 26988
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 27156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17079
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9833
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_reconnect_attempts_total 45810
telemt_me_reconnect_success_total 959
telemt_me_reader_eof_total 641
telemt_me_idle_close_by_peer_total 641
telemt_me_route_drop_no_conn_total 1020170
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1914126
telemt_me_endpoint_quarantine_total 334
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 343
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10417
telemt_desync_full_logged_total 3595
telemt_desync_suppressed_total 6822
telemt_desync_frames_bucket_total{bucket="1_2"} 1867
telemt_desync_frames_bucket_total{bucket="3_10"} 3997
telemt_desync_frames_bucket_total{bucket="gt_10"} 4553
telemt_pool_swap_total 48
telemt_pool_force_close_total 1470
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 134
telemt_me_draining_writers_reap_progress_total 16245
telemt_me_writer_removed_unexpected_total 715
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1509
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15477
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14775
telemt_me_writer_teardown_success_total{mode="normal"} 16986
telemt_me_writer_teardown_noop_total 16247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33233
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.439431
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33233
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 134
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 858
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1917746
telemt_user_connections_current{user="hello"} 1213
telemt_user_octets_from_client{user="hello"} 53836555388 (50.14 GB)
telemt_user_octets_to_client{user="hello"} 815979591854 (759.94 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 623
telemt_user_unique_ips_recent_window{user="hello"} 132
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 25473.5 (7h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194120
telemt_connections_bad_total 1644
telemt_connections_current 296
telemt_connections_me_current 296
telemt_handshake_timeouts_total 5329
telemt_upstream_connect_attempt_total 12237
telemt_upstream_connect_success_total 12207
telemt_upstream_connect_fail_total 28
telemt_upstream_connect_attempts_per_request{bucket="1"} 12235
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5165
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6966
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 28
telemt_me_reconnect_attempts_total 244
telemt_me_reconnect_success_total 159
telemt_me_reader_eof_total 163
telemt_me_idle_close_by_peer_total 163
telemt_me_route_drop_no_conn_total 53155
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171103
telemt_me_endpoint_quarantine_total 250
telemt_me_single_endpoint_shadow_rotate_total 225
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 1026
telemt_desync_full_logged_total 259
telemt_desync_suppressed_total 767
telemt_desync_frames_bucket_total{bucket="1_2"} 389
telemt_desync_frames_bucket_total{bucket="3_10"} 381
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 28
telemt_pool_force_close_total 625
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 11043
telemt_me_writer_removed_unexpected_total 156
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 720
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10486
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 623
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10418
telemt_me_writer_teardown_success_total{mode="normal"} 11206
telemt_me_writer_teardown_noop_total 11043
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 22249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 22249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 22249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 22249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 22249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 22249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 22249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 22249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 22249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 22249
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.972777
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 22249
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 145
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 170789
telemt_user_connections_current{user="hello"} 296
telemt_user_octets_from_client{user="hello"} 3076413996 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 103669361376 (96.55 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 107671.1 (29h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7310747
telemt_connections_bad_total 740906
telemt_connections_current 1504
telemt_connections_me_current 1504
telemt_handshake_timeouts_total 208361
telemt_upstream_connect_attempt_total 42149
telemt_upstream_connect_success_total 41993
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 42112
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21125
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_reconnect_attempts_total 1582
telemt_me_reconnect_success_total 848
telemt_me_reader_eof_total 831
telemt_me_idle_close_by_peer_total 831
telemt_me_route_drop_no_conn_total 2124719
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5469337
telemt_me_endpoint_quarantine_total 751
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 830
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
telemt_desync_total 21446
telemt_desync_full_logged_total 7033
telemt_desync_suppressed_total 14413
telemt_desync_frames_bucket_total{bucket="1_2"} 5392
telemt_desync_frames_bucket_total{bucket="3_10"} 7751
telemt_desync_frames_bucket_total{bucket="gt_10"} 8303
telemt_pool_swap_total 119
telemt_pool_force_close_total 3191
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 387
telemt_me_draining_writers_reap_progress_total 38000
telemt_me_writer_removed_unexpected_total 802
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2997
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35824
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3103
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34809
telemt_me_writer_teardown_success_total{mode="normal"} 38821
telemt_me_writer_teardown_noop_total 38002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75469
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 76735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 76823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 76823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 76823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 76823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 76823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 76823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 76823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 76823
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.640043
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 76823
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 387
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 758
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5444380
telemt_user_connections_current{user="hello"} 1504
telemt_user_octets_from_client{user="hello"} 109405840268 (101.89 GB)
telemt_user_octets_to_client{user="hello"} 2537398676080 (2.31 TB)
telemt_user_unique_ips_current{user="hello"} 722
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 107667.7 (29h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6306520
telemt_connections_bad_total 623170
telemt_connections_current 1611
telemt_connections_me_current 1611
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 172394
telemt_upstream_connect_attempt_total 57934
telemt_upstream_connect_success_total 57500
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 57875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_reconnect_attempts_total 5562
telemt_me_reconnect_success_total 1164
telemt_me_reader_eof_total 1051
telemt_me_idle_close_by_peer_total 1051
telemt_me_seq_mismatch_total 47
telemt_me_route_drop_no_conn_total 2177445
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4836146
telemt_me_endpoint_quarantine_total 850
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 826
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
telemt_me_writers_active_current 46
telemt_desync_total 20067
telemt_desync_full_logged_total 6681
telemt_desync_suppressed_total 13386
telemt_desync_frames_bucket_total{bucket="1_2"} 5120
telemt_desync_frames_bucket_total{bucket="3_10"} 7318
telemt_desync_frames_bucket_total{bucket="gt_10"} 7629
telemt_pool_swap_total 117
telemt_pool_force_close_total 3153
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 380
telemt_me_draining_writers_reap_progress_total 36551
telemt_me_writer_removed_unexpected_total 1060
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3517
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34147
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2930
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33398
telemt_me_writer_teardown_success_total{mode="normal"} 37664
telemt_me_writer_teardown_noop_total 36555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74219
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.078348
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74219
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 380
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 909
telemt_me_writer_restored_fallback_total 61
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4839200
telemt_user_connections_current{user="hello"} 1611
telemt_user_octets_from_client{user="hello"} 91269591513 (85.00 GB)
telemt_user_octets_to_client{user="hello"} 2066925736900 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 750
telemt_user_unique_ips_recent_window{user="hello"} 147
```