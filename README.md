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

# Server Metrics 2026-03-22 07:42:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 38179.5 (10h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 814900
telemt_connections_bad_total 50952
telemt_connections_current 1456
telemt_connections_me_current 1456
telemt_handshake_timeouts_total 39068
telemt_upstream_connect_attempt_total 15431
telemt_upstream_connect_success_total 15430
telemt_upstream_connect_attempts_per_request{bucket="1"} 15430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5343
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10039
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 37
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 430
telemt_me_reconnect_success_total 241
telemt_me_reader_eof_total 239
telemt_me_idle_close_by_peer_total 239
telemt_me_route_drop_no_conn_total 315185
telemt_me_route_drop_channel_closed_total 119
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 674961
telemt_me_endpoint_quarantine_total 276
telemt_me_single_endpoint_shadow_rotate_total 313
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_desync_total 5340
telemt_desync_full_logged_total 1513
telemt_desync_suppressed_total 3827
telemt_desync_frames_bucket_total{bucket="1_2"} 1696
telemt_desync_frames_bucket_total{bucket="3_10"} 1998
telemt_desync_frames_bucket_total{bucket="gt_10"} 1646
telemt_pool_swap_total 42
telemt_pool_force_close_total 1171
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 14013
telemt_me_writer_removed_unexpected_total 236
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 971
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13232
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12842
telemt_me_writer_teardown_success_total{mode="normal"} 14203
telemt_me_writer_teardown_noop_total 14014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28217
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 36.745703
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28217
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_removed_unexpected_minus_restored_total 15
telemt_user_connections_total{user="hello"} 673729
telemt_user_connections_current{user="hello"} 1456
telemt_user_octets_from_client{user="hello"} 9181990088 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 229710184508 (213.93 GB)
telemt_user_unique_ips_current{user="hello"} 548
telemt_user_unique_ips_recent_window{user="hello"} 215
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 51545.8 (14h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1298212
telemt_connections_bad_total 124904
telemt_connections_current 1019
telemt_connections_me_current 1019
telemt_handshake_timeouts_total 40030
telemt_upstream_connect_attempt_total 26996
telemt_upstream_connect_success_total 26592
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 26944
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13496
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13037
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1992
telemt_me_reconnect_success_total 821
telemt_me_reader_eof_total 710
telemt_me_idle_close_by_peer_total 710
telemt_me_route_drop_no_conn_total 505424
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 979285
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 415
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 4231
telemt_desync_full_logged_total 2478
telemt_desync_suppressed_total 1753
telemt_desync_frames_bucket_total{bucket="1_2"} 902
telemt_desync_frames_bucket_total{bucket="3_10"} 1636
telemt_desync_frames_bucket_total{bucket="gt_10"} 1693
telemt_pool_swap_total 55
telemt_pool_force_close_total 1480
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 21105
telemt_me_writer_removed_unexpected_total 682
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1890
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19884
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19625
telemt_me_writer_teardown_success_total{mode="normal"} 21774
telemt_me_writer_teardown_noop_total 21105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42879
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.850270
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42879
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 980953
telemt_user_connections_current{user="hello"} 1019
telemt_user_octets_from_client{user="hello"} 15410448594 (14.35 GB)
telemt_user_octets_to_client{user="hello"} 354681615291 (330.32 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 652
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 126405.6 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9200709
telemt_connections_bad_total 840410
telemt_connections_current 4268
telemt_connections_me_current 4268
telemt_handshake_timeouts_total 284230
telemt_upstream_connect_attempt_total 46664
telemt_upstream_connect_success_total 46584
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 46592
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25360
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 189
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1815
telemt_me_reconnect_success_total 925
telemt_me_reader_eof_total 928
telemt_me_idle_close_by_peer_total 928
telemt_me_route_drop_no_conn_total 5003456
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7235200
telemt_me_endpoint_quarantine_total 798
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 948
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 31440
telemt_desync_full_logged_total 10385
telemt_desync_suppressed_total 21055
telemt_desync_frames_bucket_total{bucket="1_2"} 6838
telemt_desync_frames_bucket_total{bucket="3_10"} 12196
telemt_desync_frames_bucket_total{bucket="gt_10"} 12406
telemt_pool_swap_total 137
telemt_pool_force_close_total 4521
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 42613
telemt_me_writer_removed_unexpected_total 892
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3539
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4245
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 276
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38092
telemt_me_writer_teardown_success_total{mode="normal"} 42995
telemt_me_writer_teardown_noop_total 42657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85652
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 180.681292
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85652
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 47
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 7225691
telemt_user_connections_current{user="hello"} 4268
telemt_user_octets_from_client{user="hello"} 121032050764 (112.72 GB)
telemt_user_octets_to_client{user="hello"} 2457401729436 (2.23 TB)
telemt_user_unique_ips_current{user="hello"} 1688
telemt_user_unique_ips_recent_window{user="hello"} 720
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 126406.9 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7559783
telemt_connections_bad_total 671917
telemt_connections_current 4334
telemt_connections_me_current 4334
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 246578
telemt_upstream_connect_attempt_total 50637
telemt_upstream_connect_success_total 50230
telemt_upstream_connect_fail_total 210
telemt_upstream_connect_attempts_per_request{bucket="1"} 50440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24753
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24882
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 562
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 210
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2674
telemt_me_reconnect_success_total 995
telemt_me_reader_eof_total 962
telemt_me_idle_close_by_peer_total 962
telemt_me_route_drop_no_conn_total 2530496
telemt_me_route_drop_channel_closed_total 308
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5602723
telemt_me_endpoint_quarantine_total 801
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 973
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 25758
telemt_desync_full_logged_total 8832
telemt_desync_suppressed_total 16926
telemt_desync_frames_bucket_total{bucket="1_2"} 6153
telemt_desync_frames_bucket_total{bucket="3_10"} 9990
telemt_desync_frames_bucket_total{bucket="gt_10"} 9615
telemt_pool_swap_total 138
telemt_pool_force_close_total 4135
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 431
telemt_me_draining_writers_reap_progress_total 41041
telemt_me_writer_removed_unexpected_total 938
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3412
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38486
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3894
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 241
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36906
telemt_me_writer_teardown_success_total{mode="normal"} 41898
telemt_me_writer_teardown_noop_total 41047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82720
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82945
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.513526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82945
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 431
telemt_me_refill_failed_total 94
telemt_me_writer_restored_same_endpoint_total 869
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 5523542
telemt_user_connections_current{user="hello"} 4334
telemt_user_octets_from_client{user="hello"} 156119447437 (145.40 GB)
telemt_user_octets_to_client{user="hello"} 2671479925951 (2.43 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1662
telemt_user_unique_ips_recent_window{user="hello"} 581
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 126370.9 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7308054
telemt_connections_bad_total 602766
telemt_connections_current 3433
telemt_connections_me_current 3433
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 242453
telemt_upstream_connect_attempt_total 57277
telemt_upstream_connect_success_total 56608
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 56755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27890
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26527
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1293
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2736
telemt_me_reconnect_success_total 1189
telemt_me_reader_eof_total 1097
telemt_me_idle_close_by_peer_total 1097
telemt_me_route_drop_no_conn_total 2954571
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5453318
telemt_me_endpoint_quarantine_total 891
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 936
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
telemt_me_writers_active_current 46
telemt_desync_total 25396
telemt_desync_full_logged_total 8668
telemt_desync_suppressed_total 16728
telemt_desync_frames_bucket_total{bucket="1_2"} 6161
telemt_desync_frames_bucket_total{bucket="3_10"} 9751
telemt_desync_frames_bucket_total{bucket="gt_10"} 9484
telemt_pool_swap_total 135
telemt_pool_force_close_total 3990
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 458
telemt_me_draining_writers_reap_progress_total 41991
telemt_me_writer_removed_unexpected_total 1107
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3724
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39378
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3692
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 298
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38001
telemt_me_writer_teardown_success_total{mode="normal"} 43102
telemt_me_writer_teardown_noop_total 42003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85105
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 43.836064
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85105
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 458
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1030
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 5446706
telemt_user_connections_current{user="hello"} 3433
telemt_user_octets_from_client{user="hello"} 144277118215 (134.37 GB)
telemt_user_octets_to_client{user="hello"} 2424965370863 (2.21 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1462
telemt_user_unique_ips_recent_window{user="hello"} 512
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 126410.1 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23406916
telemt_connections_bad_total 1942629
telemt_connections_current 5356
telemt_connections_me_current 5356
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 685090
telemt_upstream_connect_attempt_total 240870
telemt_upstream_connect_success_total 221131
telemt_upstream_connect_fail_total 17756
telemt_upstream_connect_attempts_per_request{bucket="1"} 238887
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155015
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52219
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17756
telemt_me_keepalive_timeout_total 414
telemt_me_reconnect_attempts_total 66507
telemt_me_reconnect_success_total 2687
telemt_me_reader_eof_total 1667
telemt_me_idle_close_by_peer_total 1665
telemt_me_route_drop_no_conn_total 44888551
telemt_me_route_drop_channel_closed_total 143
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18881974
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 985
telemt_me_single_endpoint_outage_enter_total 164
telemt_me_single_endpoint_outage_exit_total 164
telemt_me_single_endpoint_outage_reconnect_attempt_total 335
telemt_me_single_endpoint_outage_reconnect_success_total 86
telemt_me_single_endpoint_quarantine_bypass_total 335
telemt_me_single_endpoint_shadow_rotate_total 994
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 71
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
telemt_desync_total 36548
telemt_desync_full_logged_total 10866
telemt_desync_suppressed_total 25682
telemt_desync_frames_bucket_total{bucket="1_2"} 8070
telemt_desync_frames_bucket_total{bucket="3_10"} 16154
telemt_desync_frames_bucket_total{bucket="gt_10"} 12324
telemt_pool_swap_total 131
telemt_pool_force_close_total 4154
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 958
telemt_me_draining_writers_reap_progress_total 39439
telemt_me_writer_removed_unexpected_total 2490
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5354
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36306
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3565
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 589
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35285
telemt_me_writer_teardown_success_total{mode="normal"} 41660
telemt_me_writer_teardown_noop_total 39471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77725
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80626
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81131
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 283.180731
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81131
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 958
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1816
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14757
telemt_me_writer_removed_unexpected_minus_restored_total 652
telemt_user_connections_total{user="hello"} 19047681
telemt_user_connections_current{user="hello"} 5356
telemt_user_octets_from_client{user="hello"} 274791252379 (255.92 GB)
telemt_user_octets_to_client{user="hello"} 1416886969295 (1.29 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2030
telemt_user_unique_ips_recent_window{user="hello"} 1062
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 126377.5 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6960994
telemt_connections_bad_total 636534
telemt_connections_current 4235
telemt_connections_me_current 4235
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 144153
telemt_upstream_connect_attempt_total 65678
telemt_upstream_connect_success_total 64931
telemt_upstream_connect_fail_total 641
telemt_upstream_connect_attempts_per_request{bucket="1"} 65572
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27438
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 641
telemt_me_reconnect_attempts_total 70103
telemt_me_reconnect_success_total 1939
telemt_me_reader_eof_total 1715
telemt_me_idle_close_by_peer_total 1714
telemt_me_route_drop_no_conn_total 2674380
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5453895
telemt_me_endpoint_quarantine_total 844
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 961
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 27451
telemt_desync_full_logged_total 9560
telemt_desync_suppressed_total 17891
telemt_desync_frames_bucket_total{bucket="1_2"} 5480
telemt_desync_frames_bucket_total{bucket="3_10"} 10559
telemt_desync_frames_bucket_total{bucket="gt_10"} 11412
telemt_pool_swap_total 132
telemt_pool_force_close_total 3796
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 448
telemt_me_draining_writers_reap_progress_total 44182
telemt_me_writer_removed_unexpected_total 1746
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4429
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41536
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3377
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40386
telemt_me_writer_teardown_success_total{mode="normal"} 45965
telemt_me_writer_teardown_noop_total 44183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90148
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.080235
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90148
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 448
telemt_me_refill_failed_total 4221
telemt_me_writer_restored_same_endpoint_total 1618
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 5444906
telemt_user_connections_current{user="hello"} 4235
telemt_user_octets_from_client{user="hello"} 138170446352 (128.68 GB)
telemt_user_octets_to_client{user="hello"} 2276186467110 (2.07 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1679
telemt_user_unique_ips_recent_window{user="hello"} 915
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 63213.4 (17h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5275719
telemt_connections_bad_total 211986
telemt_connections_current 3119
telemt_connections_me_current 3119
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2099966
telemt_upstream_connect_attempt_total 34595
telemt_upstream_connect_success_total 34353
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 34588
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 88
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_reconnect_attempts_total 46313
telemt_me_reconnect_success_total 1086
telemt_me_reader_eof_total 778
telemt_me_idle_close_by_peer_total 778
telemt_me_route_drop_no_conn_total 1288974
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2627548
telemt_me_endpoint_quarantine_total 441
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 486
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 14049
telemt_desync_full_logged_total 4830
telemt_desync_suppressed_total 9219
telemt_desync_frames_bucket_total{bucket="1_2"} 2778
telemt_desync_frames_bucket_total{bucket="3_10"} 5376
telemt_desync_frames_bucket_total{bucket="gt_10"} 5895
telemt_pool_swap_total 69
telemt_pool_force_close_total 2031
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 22928
telemt_me_writer_removed_unexpected_total 848
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1937
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21861
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1800
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 231
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20897
telemt_me_writer_teardown_success_total{mode="normal"} 23798
telemt_me_writer_teardown_noop_total 22930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46728
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.280793
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46728
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 2627
telemt_me_writer_restored_same_endpoint_total 965
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2629069
telemt_user_connections_current{user="hello"} 3119
telemt_user_octets_from_client{user="hello"} 66803736072 (62.22 GB)
telemt_user_octets_to_client{user="hello"} 1165760498970 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1237
telemt_user_unique_ips_recent_window{user="hello"} 1142
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 44184.4 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353345
telemt_connections_bad_total 2466
telemt_connections_current 820
telemt_connections_me_current 820
telemt_handshake_timeouts_total 7774
telemt_upstream_connect_attempt_total 21060
telemt_upstream_connect_success_total 21005
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 21055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12046
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 905
telemt_me_reconnect_success_total 308
telemt_me_reader_eof_total 304
telemt_me_idle_close_by_peer_total 304
telemt_me_route_drop_no_conn_total 109288
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 320425
telemt_me_endpoint_quarantine_total 417
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 380
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_warm_current 33
telemt_desync_total 1514
telemt_desync_full_logged_total 429
telemt_desync_suppressed_total 1085
telemt_desync_frames_bucket_total{bucket="1_2"} 482
telemt_desync_frames_bucket_total{bucket="3_10"} 582
telemt_desync_frames_bucket_total{bucket="gt_10"} 450
telemt_pool_swap_total 48
telemt_pool_force_close_total 1086
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 19011
telemt_me_writer_removed_unexpected_total 291
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1237
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18078
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1084
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17925
telemt_me_writer_teardown_success_total{mode="normal"} 19315
telemt_me_writer_teardown_noop_total 19011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38316
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38326
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38326
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.590757
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38326
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 262
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 319879
telemt_user_connections_current{user="hello"} 820
telemt_user_octets_from_client{user="hello"} 5473913400 (5.10 GB)
telemt_user_octets_to_client{user="hello"} 176441255380 (164.32 GB)
telemt_user_unique_ips_current{user="hello"} 321
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 126382.0 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8524724
telemt_connections_bad_total 928192
telemt_connections_current 4675
telemt_connections_me_current 4675
telemt_handshake_timeouts_total 239882
telemt_upstream_connect_attempt_total 49458
telemt_upstream_connect_success_total 49277
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 49419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24824
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_reconnect_attempts_total 1835
telemt_me_reconnect_success_total 998
telemt_me_reader_eof_total 975
telemt_me_idle_close_by_peer_total 975
telemt_me_route_drop_no_conn_total 2388001
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6331955
telemt_me_endpoint_quarantine_total 895
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 964
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
telemt_desync_total 25306
telemt_desync_full_logged_total 8315
telemt_desync_suppressed_total 16991
telemt_desync_frames_bucket_total{bucket="1_2"} 6283
telemt_desync_frames_bucket_total{bucket="3_10"} 9211
telemt_desync_frames_bucket_total{bucket="gt_10"} 9812
telemt_pool_swap_total 140
telemt_pool_force_close_total 3749
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 449
telemt_me_draining_writers_reap_progress_total 44637
telemt_me_writer_removed_unexpected_total 937
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3530
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42072
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3653
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 96
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40888
telemt_me_writer_teardown_success_total{mode="normal"} 45602
telemt_me_writer_teardown_noop_total 44639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 89744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 90150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 90241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 90241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 90241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 90241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 90241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 90241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 90241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 90241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 90241
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.545273
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 90241
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 449
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 882
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6305503
telemt_user_connections_current{user="hello"} 4675
telemt_user_octets_from_client{user="hello"} 124493351932 (115.94 GB)
telemt_user_octets_to_client{user="hello"} 2958035938164 (2.69 TB)
telemt_user_unique_ips_current{user="hello"} 1740
telemt_user_unique_ips_recent_window{user="hello"} 641
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 126378.5 (35h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7445968
telemt_connections_bad_total 806291
telemt_connections_current 3797
telemt_connections_me_current 3797
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 199646
telemt_upstream_connect_attempt_total 65479
telemt_upstream_connect_success_total 64975
telemt_upstream_connect_fail_total 441
telemt_upstream_connect_attempts_per_request{bucket="1"} 65416
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37289
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26544
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 441
telemt_me_reconnect_attempts_total 6121
telemt_me_reconnect_success_total 1407
telemt_me_reader_eof_total 1265
telemt_me_idle_close_by_peer_total 1265
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2491182
telemt_me_route_drop_channel_closed_total 205
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5664357
telemt_me_endpoint_quarantine_total 992
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 961
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_active_current 48
telemt_desync_total 24253
telemt_desync_full_logged_total 8063
telemt_desync_suppressed_total 16190
telemt_desync_frames_bucket_total{bucket="1_2"} 5981
telemt_desync_frames_bucket_total{bucket="3_10"} 8906
telemt_desync_frames_bucket_total{bucket="gt_10"} 9366
telemt_pool_swap_total 137
telemt_pool_force_close_total 3693
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 448
telemt_me_draining_writers_reap_progress_total 43288
telemt_me_writer_removed_unexpected_total 1280
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4131
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40498
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39595
telemt_me_writer_teardown_success_total{mode="normal"} 44629
telemt_me_writer_teardown_noop_total 43292
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 86029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 87217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 87658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 87883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 87921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87921
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.602907
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87921
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 448
telemt_me_refill_failed_total 272
telemt_me_writer_restored_same_endpoint_total 1102
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 102
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 5665859
telemt_user_connections_current{user="hello"} 3797
telemt_user_octets_from_client{user="hello"} 104570054025 (97.39 GB)
telemt_user_octets_to_client{user="hello"} 2462699903648 (2.24 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1499
telemt_user_unique_ips_recent_window{user="hello"} 524
```