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

# Server Metrics 2026-03-23 05:46:26 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 117601.7 (32h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4183036
telemt_connections_bad_total 397091
telemt_connections_current 1460
telemt_connections_me_current 1460
telemt_handshake_timeouts_total 139634
telemt_upstream_connect_attempt_total 43742
telemt_upstream_connect_success_total 43741
telemt_upstream_connect_attempts_per_request{bucket="1"} 43741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28383
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 879
telemt_me_reconnect_attempts_total 1537
telemt_me_reconnect_success_total 682
telemt_me_reader_eof_total 705
telemt_me_idle_close_by_peer_total 705
telemt_me_route_drop_no_conn_total 3438990
telemt_me_route_drop_channel_closed_total 1332
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3424929
telemt_me_writer_pick_total{mode="p2c",result="full"} 18
telemt_me_endpoint_quarantine_total 836
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 921
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
telemt_me_writers_active_current 45
telemt_desync_total 14151
telemt_desync_full_logged_total 4493
telemt_desync_suppressed_total 9658
telemt_desync_frames_bucket_total{bucket="1_2"} 3663
telemt_desync_frames_bucket_total{bucket="3_10"} 5262
telemt_desync_frames_bucket_total{bucket="gt_10"} 5226
telemt_pool_swap_total 130
telemt_pool_force_close_total 3976
telemt_pool_stale_pick_total 36
telemt_me_writer_close_signal_drop_total 758
telemt_me_draining_writers_reap_progress_total 40090
telemt_me_writer_removed_unexpected_total 678
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2869
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37499
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36114
telemt_me_writer_teardown_success_total{mode="normal"} 40368
telemt_me_writer_teardown_noop_total 40103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 77887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80471
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 435.607367
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80471
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 758
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 611
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 3412330
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 45642650976 (42.51 GB)
telemt_user_octets_to_client{user="hello"} 895919415592 (834.39 GB)
telemt_user_unique_ips_current{user="hello"} 592
telemt_user_unique_ips_recent_window{user="hello"} 234
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 130967.8 (36h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4166096
telemt_connections_bad_total 386751
telemt_connections_current 860
telemt_connections_me_current 860
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 108611
telemt_upstream_connect_attempt_total 81601
telemt_upstream_connect_success_total 80619
telemt_upstream_connect_fail_total 870
telemt_upstream_connect_attempts_per_request{bucket="1"} 81489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44397
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35995
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 227
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 870
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 11010
telemt_me_reconnect_success_total 3957
telemt_me_reader_eof_total 3928
telemt_me_idle_close_by_peer_total 3927
telemt_me_route_drop_no_conn_total 3674249
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3303837
telemt_me_endpoint_quarantine_total 1064
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 54
telemt_me_single_endpoint_outage_exit_total 54
telemt_me_single_endpoint_outage_reconnect_attempt_total 55
telemt_me_single_endpoint_outage_reconnect_success_total 53
telemt_me_single_endpoint_quarantine_bypass_total 55
telemt_me_single_endpoint_shadow_rotate_total 1032
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_active_current 88
telemt_desync_total 13583
telemt_desync_full_logged_total 7660
telemt_desync_suppressed_total 5923
telemt_desync_frames_bucket_total{bucket="1_2"} 3089
telemt_desync_frames_bucket_total{bucket="3_10"} 5328
telemt_desync_frames_bucket_total{bucket="gt_10"} 5166
telemt_pool_swap_total 123
telemt_pool_force_close_total 3417
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 262
telemt_me_draining_writers_reap_progress_total 54913
telemt_me_writer_removed_unexpected_total 3850
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6946
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51859
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2932
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 485
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51496
telemt_me_writer_teardown_success_total{mode="normal"} 58805
telemt_me_writer_teardown_noop_total 54914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113719
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.958733
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113719
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 262
telemt_me_refill_failed_total 279
telemt_me_writer_restored_same_endpoint_total 3504
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 49
telemt_me_writer_removed_unexpected_minus_restored_total 315
telemt_user_connections_total{user="hello"} 3318265
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 44652933883 (41.59 GB)
telemt_user_octets_to_client{user="hello"} 838371961937 (780.79 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 514
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 205827.8 (57h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16700565
telemt_connections_bad_total 1690787
telemt_connections_current 1730
telemt_connections_me_current 1730
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 409166
telemt_upstream_connect_attempt_total 92384
telemt_upstream_connect_success_total 92273
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 92290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44909
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45625
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1732
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3269
telemt_me_reconnect_success_total 1697
telemt_me_reader_eof_total 1656
telemt_me_idle_close_by_peer_total 1653
telemt_me_route_drop_no_conn_total 14125179
telemt_me_route_drop_channel_closed_total 146
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13268436
telemt_me_endpoint_quarantine_total 1396
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1560
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
telemt_me_writers_active_current 43
telemt_desync_total 55393
telemt_desync_full_logged_total 17711
telemt_desync_suppressed_total 37682
telemt_desync_frames_bucket_total{bucket="1_2"} 12355
telemt_desync_frames_bucket_total{bucket="3_10"} 21707
telemt_desync_frames_bucket_total{bucket="gt_10"} 21331
telemt_pool_swap_total 223
telemt_pool_force_close_total 7150
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1106
telemt_me_draining_writers_reap_progress_total 71151
telemt_me_writer_removed_unexpected_total 1589
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5969
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 66057
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 64001
telemt_me_writer_teardown_success_total{mode="normal"} 72026
telemt_me_writer_teardown_noop_total 71205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135658
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 137486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 142621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 143192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 143222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 143223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 143227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 143229
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 143231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 143231
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 319.330470
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 143231
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1106
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1469
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 13268239
telemt_user_connections_current{user="hello"} 1730
telemt_user_octets_from_client{user="hello"} 200848432029 (187.05 GB)
telemt_user_octets_to_client{user="hello"} 3606256253439 (3.28 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 634
telemt_user_unique_ips_recent_window{user="hello"} 235
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 205829.0 (57h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12199198
telemt_connections_bad_total 1293587
telemt_connections_current 1091
telemt_connections_me_current 1091
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 353662
telemt_upstream_connect_attempt_total 106829
telemt_upstream_connect_success_total 105415
telemt_upstream_connect_fail_total 900
telemt_upstream_connect_attempts_per_request{bucket="1"} 106315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55795
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 900
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4721
telemt_me_reconnect_success_total 2031
telemt_me_reader_eof_total 1895
telemt_me_idle_close_by_peer_total 1895
telemt_me_route_drop_no_conn_total 4616109
telemt_me_route_drop_channel_closed_total 505
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9022721
telemt_me_endpoint_quarantine_total 1404
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1576
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 57
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
telemt_desync_total 39690
telemt_desync_full_logged_total 13395
telemt_desync_suppressed_total 26295
telemt_desync_frames_bucket_total{bucket="1_2"} 9847
telemt_desync_frames_bucket_total{bucket="3_10"} 15233
telemt_desync_frames_bucket_total{bucket="gt_10"} 14610
telemt_pool_swap_total 220
telemt_pool_force_close_total 6493
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 722
telemt_me_draining_writers_reap_progress_total 69286
telemt_me_writer_removed_unexpected_total 1925
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6069
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65005
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5981
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62793
telemt_me_writer_teardown_success_total{mode="normal"} 71074
telemt_me_writer_teardown_noop_total 69311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 133591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 136855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139960
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140383
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140385
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140385
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.715695
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140385
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 722
telemt_me_refill_failed_total 144
telemt_me_writer_restored_same_endpoint_total 1736
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 8960256
telemt_user_connections_current{user="hello"} 1091
telemt_user_octets_from_client{user="hello"} 220610900648 (205.46 GB)
telemt_user_octets_to_client{user="hello"} 4037143383579 (3.67 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 448
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 205793.1 (57h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11349265
telemt_connections_bad_total 1042395
telemt_connections_current 1017
telemt_connections_me_current 1017
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 359414
telemt_upstream_connect_attempt_total 91234
telemt_upstream_connect_success_total 89656
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 89861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41020
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 44188
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5916
telemt_me_reconnect_success_total 2496
telemt_me_reader_eof_total 2238
telemt_me_idle_close_by_peer_total 2237
telemt_me_route_drop_no_conn_total 5385316
telemt_me_route_drop_channel_closed_total 386
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8530613
telemt_me_endpoint_quarantine_total 1454
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 1539
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 75
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
telemt_desync_total 38805
telemt_desync_full_logged_total 12890
telemt_desync_suppressed_total 25915
telemt_desync_frames_bucket_total{bucket="1_2"} 9790
telemt_desync_frames_bucket_total{bucket="3_10"} 14862
telemt_desync_frames_bucket_total{bucket="gt_10"} 14153
telemt_pool_swap_total 216
telemt_pool_force_close_total 6381
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 763
telemt_me_draining_writers_reap_progress_total 69911
telemt_me_writer_removed_unexpected_total 2383
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6822
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65409
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5807
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 574
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63530
telemt_me_writer_teardown_success_total{mode="normal"} 72231
telemt_me_writer_teardown_noop_total 69982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 136360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 139093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 140058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 141131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 141732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 141946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 142074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 142105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 142113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 142126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 142159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 142162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 142213
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.979894
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 142213
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 763
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2172
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8522375
telemt_user_connections_current{user="hello"} 1017
telemt_user_octets_from_client{user="hello"} 194359804659 (181.01 GB)
telemt_user_octets_to_client{user="hello"} 3534166086361 (3.21 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 76073.2 (21h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11723931
telemt_connections_bad_total 709347
telemt_connections_current 2046
telemt_connections_me_current 2046
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 322025
telemt_upstream_connect_attempt_total 67901
telemt_upstream_connect_success_total 64311
telemt_upstream_connect_fail_total 2319
telemt_upstream_connect_attempts_per_request{bucket="1"} 66630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33429
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2319
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8464
telemt_me_reconnect_success_total 1579
telemt_me_reader_eof_total 998
telemt_me_idle_close_by_peer_total 997
telemt_me_route_drop_no_conn_total 25389300
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9685700
telemt_me_endpoint_quarantine_total 606
telemt_me_single_endpoint_outage_enter_total 111
telemt_me_single_endpoint_outage_exit_total 111
telemt_me_single_endpoint_outage_reconnect_attempt_total 213
telemt_me_single_endpoint_outage_reconnect_success_total 56
telemt_me_single_endpoint_quarantine_bypass_total 213
telemt_me_single_endpoint_shadow_rotate_total 613
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 17425
telemt_desync_full_logged_total 4887
telemt_desync_suppressed_total 12538
telemt_desync_frames_bucket_total{bucket="1_2"} 3371
telemt_desync_frames_bucket_total{bucket="3_10"} 7134
telemt_desync_frames_bucket_total{bucket="gt_10"} 6920
telemt_pool_swap_total 78
telemt_pool_force_close_total 2443
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 533
telemt_me_draining_writers_reap_progress_total 25249
telemt_me_writer_removed_unexpected_total 1455
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3264
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23392
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2096
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 347
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22806
telemt_me_writer_teardown_success_total{mode="normal"} 26656
telemt_me_writer_teardown_noop_total 25268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51924
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51924
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 55.154110
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51924
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 533
telemt_me_refill_failed_total 350
telemt_me_writer_restored_same_endpoint_total 1010
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 9713208
telemt_user_connections_current{user="hello"} 2046
telemt_user_octets_from_client{user="hello"} 91242700979 (84.98 GB)
telemt_user_octets_to_client{user="hello"} 739884006833 (689.07 GB)
telemt_user_msgs_from_client{user="hello"} 71666
telemt_user_msgs_to_client{user="hello"} 62721
telemt_user_unique_ips_current{user="hello"} 719
telemt_user_unique_ips_recent_window{user="hello"} 286
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 205799.7 (57h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11322134
telemt_connections_bad_total 996652
telemt_connections_current 1417
telemt_connections_me_current 1417
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 255735
telemt_upstream_connect_attempt_total 120218
telemt_upstream_connect_success_total 118955
telemt_upstream_connect_fail_total 1086
telemt_upstream_connect_attempts_per_request{bucket="1"} 120041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69691
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47646
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1086
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73586
telemt_me_reconnect_success_total 3282
telemt_me_reader_eof_total 2967
telemt_me_idle_close_by_peer_total 2964
telemt_me_route_drop_no_conn_total 5329388
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8912470
telemt_me_endpoint_quarantine_total 1400
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 47
telemt_me_single_endpoint_outage_reconnect_success_total 45
telemt_me_single_endpoint_quarantine_bypass_total 47
telemt_me_single_endpoint_shadow_rotate_total 1566
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_me_writers_active_current 50
telemt_desync_total 47473
telemt_desync_full_logged_total 16330
telemt_desync_suppressed_total 31143
telemt_desync_frames_bucket_total{bucket="1_2"} 9652
telemt_desync_frames_bucket_total{bucket="3_10"} 18200
telemt_desync_frames_bucket_total{bucket="gt_10"} 19621
telemt_pool_swap_total 212
telemt_pool_force_close_total 6096
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 687
telemt_me_draining_writers_reap_progress_total 74019
telemt_me_writer_removed_unexpected_total 2984
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7353
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 69697
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67923
telemt_me_writer_teardown_success_total{mode="normal"} 77050
telemt_me_writer_teardown_noop_total 74020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 150753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151070
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.389295
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151070
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 687
telemt_me_refill_failed_total 4323
telemt_me_writer_restored_same_endpoint_total 2760
telemt_me_writer_restored_fallback_total 58
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7371
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 8915061
telemt_user_connections_current{user="hello"} 1417
telemt_user_octets_from_client{user="hello"} 199432746089 (185.74 GB)
telemt_user_octets_to_client{user="hello"} 3413011813384 (3.10 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 563
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 142636.1 (39h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12114649
telemt_connections_bad_total 494307
telemt_connections_current 1099
telemt_connections_me_current 1099
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4888185
telemt_upstream_connect_attempt_total 69185
telemt_upstream_connect_success_total 68695
telemt_upstream_connect_fail_total 477
telemt_upstream_connect_attempts_per_request{bucket="1"} 69172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 477
telemt_me_reconnect_attempts_total 49393
telemt_me_reconnect_success_total 1979
telemt_me_reader_eof_total 1665
telemt_me_idle_close_by_peer_total 1664
telemt_me_route_drop_no_conn_total 4150929
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5821414
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1102
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32742
telemt_desync_full_logged_total 11202
telemt_desync_suppressed_total 21540
telemt_desync_frames_bucket_total{bucket="1_2"} 6589
telemt_desync_frames_bucket_total{bucket="3_10"} 12886
telemt_desync_frames_bucket_total{bucket="gt_10"} 13267
telemt_pool_swap_total 152
telemt_pool_force_close_total 4289
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 53940
telemt_me_writer_removed_unexpected_total 1702
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4268
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51432
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3845
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49651
telemt_me_writer_teardown_success_total{mode="normal"} 55700
telemt_me_writer_teardown_noop_total 53947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108312
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 109420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 109647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 109647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 109647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 109647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 109647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 109647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 109647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 109647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 109647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 109647
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.875245
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 109647
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 2754
telemt_me_writer_restored_same_endpoint_total 1749
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5813264
telemt_user_connections_current{user="hello"} 1099
telemt_user_octets_from_client{user="hello"} 122023156740 (113.64 GB)
telemt_user_octets_to_client{user="hello"} 2265641725638 (2.06 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 457
telemt_user_unique_ips_recent_window{user="hello"} 185
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 123606.8 (34h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1717822
telemt_connections_bad_total 37632
telemt_connections_current 805
telemt_connections_me_current 805
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 37613
telemt_upstream_connect_attempt_total 58190
telemt_upstream_connect_success_total 57995
telemt_upstream_connect_fail_total 157
telemt_upstream_connect_attempts_per_request{bucket="1"} 58152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27530
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29613
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 852
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 157
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2520
telemt_me_reconnect_success_total 1026
telemt_me_reader_eof_total 1022
telemt_me_idle_close_by_peer_total 1022
telemt_me_route_drop_no_conn_total 580071
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1525721
telemt_me_endpoint_quarantine_total 1054
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1018
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 10484
telemt_desync_full_logged_total 2959
telemt_desync_suppressed_total 7525
telemt_desync_frames_bucket_total{bucket="1_2"} 3306
telemt_desync_frames_bucket_total{bucket="3_10"} 3928
telemt_desync_frames_bucket_total{bucket="gt_10"} 3250
telemt_pool_swap_total 134
telemt_pool_force_close_total 3387
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 179
telemt_me_draining_writers_reap_progress_total 49637
telemt_me_writer_removed_unexpected_total 984
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3749
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46920
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3299
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46250
telemt_me_writer_teardown_success_total{mode="normal"} 50669
telemt_me_writer_teardown_noop_total 49641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100310
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.720826
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100310
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 179
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 880
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1521265
telemt_user_connections_current{user="hello"} 805
telemt_user_octets_from_client{user="hello"} 27789601145 (25.88 GB)
telemt_user_octets_to_client{user="hello"} 619247494239 (576.72 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 312
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 205804.3 (57h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13601862
telemt_connections_bad_total 1643684
telemt_connections_current 1383
telemt_connections_me_current 1383
telemt_handshake_timeouts_total 398917
telemt_upstream_connect_attempt_total 83037
telemt_upstream_connect_success_total 82669
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 82899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3287
telemt_me_reconnect_success_total 1634
telemt_me_reader_eof_total 1627
telemt_me_idle_close_by_peer_total 1627
telemt_me_route_drop_no_conn_total 4537165
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 44
telemt_me_route_drop_queue_full_profile_total{profile="high"} 44
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10257666
telemt_me_endpoint_quarantine_total 1527
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1565
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 43082
telemt_desync_full_logged_total 14055
telemt_desync_suppressed_total 29027
telemt_desync_frames_bucket_total{bucket="1_2"} 10486
telemt_desync_frames_bucket_total{bucket="3_10"} 15820
telemt_desync_frames_bucket_total{bucket="gt_10"} 16776
telemt_pool_swap_total 228
telemt_pool_force_close_total 5946
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 705
telemt_me_draining_writers_reap_progress_total 75166
telemt_me_writer_removed_unexpected_total 1555
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5771
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71012
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5772
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69220
telemt_me_writer_teardown_success_total{mode="normal"} 76783
telemt_me_writer_teardown_noop_total 75168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 149294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 151056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 151442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151951
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.055874
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151951
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 705
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 1436
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 10224059
telemt_user_connections_current{user="hello"} 1383
telemt_user_octets_from_client{user="hello"} 197229803432 (183.68 GB)
telemt_user_octets_to_client{user="hello"} 4561058139740 (4.15 TB)
telemt_user_unique_ips_current{user="hello"} 513
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 205800.9 (57h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11914070
telemt_connections_bad_total 1390478
telemt_connections_current 1120
telemt_connections_me_current 1120
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 320757
telemt_upstream_connect_attempt_total 110966
telemt_upstream_connect_success_total 110014
telemt_upstream_connect_fail_total 743
telemt_upstream_connect_attempts_per_request{bucket="1"} 110757
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47309
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 743
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11122
telemt_me_reconnect_success_total 2769
telemt_me_reader_eof_total 2572
telemt_me_idle_close_by_peer_total 2571
telemt_me_seq_mismatch_total 109
telemt_me_route_drop_no_conn_total 5705847
telemt_me_route_drop_channel_closed_total 355
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9178223
telemt_me_endpoint_quarantine_total 1702
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1571
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42700
telemt_desync_full_logged_total 13757
telemt_desync_suppressed_total 28943
telemt_desync_frames_bucket_total{bucket="1_2"} 11092
telemt_desync_frames_bucket_total{bucket="3_10"} 15684
telemt_desync_frames_bucket_total{bucket="gt_10"} 15924
telemt_pool_swap_total 218
telemt_pool_force_close_total 5695
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 686
telemt_me_draining_writers_reap_progress_total 75600
telemt_me_writer_removed_unexpected_total 2608
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7184
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 71126
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5224
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 69905
telemt_me_writer_teardown_success_total{mode="normal"} 78310
telemt_me_writer_teardown_noop_total 75605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 151171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 152992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 153546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 153865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 153915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 153915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 153915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 153915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 153915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 153915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 153915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 153915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 153915
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.851399
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 153915
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 686
telemt_me_refill_failed_total 434
telemt_me_writer_restored_same_endpoint_total 2207
telemt_me_writer_restored_fallback_total 144
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 257
telemt_user_connections_total{user="hello"} 9182553
telemt_user_connections_current{user="hello"} 1120
telemt_user_octets_from_client{user="hello"} 159910621212 (148.93 GB)
telemt_user_octets_to_client{user="hello"} 3594190784982 (3.27 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 484
telemt_user_unique_ips_recent_window{user="hello"} 173
```